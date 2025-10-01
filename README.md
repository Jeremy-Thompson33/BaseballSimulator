## ⚾ Baseball Simulator
##### 🧑‍💻 **By Jeremy Thompson**
### 📖 Project Overview
This project is a baseball simulation engine that models offensive production for a given MLB lineup. The model uses live player data to improve simulation accuracy and usefulness throughout the season. By using the simulator, important strategic questions can be answered for individual teams and for the MLB as a whole. 

I built this to combine my interests in sports analytics, probability modeling, and algorithm design — while also showcasing practical skills in Python, web scraping, data structures, and optimization techniques.


## 🛠️ What I Built & Learned
### Webscraping and Data Wrangling
- Used Selenium to scrape dynamic data from various sources.
- 

### 🎲 Simulation Engine
- Developed a stochastic game simulator that models outcomes (strikeouts, walks, singles, doubles, HRs, etc.) based on player stats.
- Designed a BaseRunners system to track runner advancement, outs, and runs in real time.
- Implemented probability-driven outcomes using random number generation weighted by real performance metrics.

### 📊 Data & Modeling
- Encoded player stats (OBP, strikeout %, ground ball %, etc.) into probabilistic models.
- Ran Monte Carlo simulations (1,000s of games) to calculate expected runs for each lineup.
- Learned how variance/noise in simulation affects optimization and experimented with ways to stabilize results.

### 🤖 Optimization Algorithms
- Brute force search for small player pools.
- Genetic Algorithm for scalable optimization:
- Population generation, fitness evaluation, elitism, crossover, and mutation.
- Cached fitness scores for efficiency.
- Balanced exploration vs. exploitation by tuning hyperparameters (population size, generations, elite size, mutation rate).

### 💡 Key Skills Demonstrated
- Python programming (object-oriented design, algorithms, optimization).
- Probability & statistics (Monte Carlo simulation, distributions, variance analysis).
- Machine learning concepts (evolutionary algorithms, stochastic optimization).
- Data analysis & visualization (tracking convergence of GA runs, comparing lineup performance).
- Performance tuning (profiling bottlenecks, reducing simulation noise).
