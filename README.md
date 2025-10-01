# ⚾ Baseball Simulator
### 🧑‍💻 By Jeremy Thompson

## 📖 Project Overview
This project is an end-to-end baseball analytics simulator that combines **web scraping, data wrangling, simulation modeling, and optimization** to answer strategic baseball questions and identify optimal batting orders.

I built this project to demonstrate my ability to:
- Collect and clean messy real-world data.
- Model complex, probabilistic systems with object-oriented Python.
- Apply optimization techniques like **Genetic Algorithms**.
- Communicate results through **data visualization and scenario analysis**.

## ⚙️ Tools and Technologies
- **Python** (core simulation, classes, and algorithms)
- **Selenium** (web scraping of dynamic MLB stats)
- **Pandas** (data cleaning, structuring, merging)
- **NumPy** (probability modeling, vectorized calculations)
- **Matplotlib** (data visualization & scenario comparisons)

## 🛠️ Features and Skills Demonstrated
### 🔎 Data Collection & Wrangling
**Web Scraping:**
- Used Selenium to scrape dynamic MLB statistics from multiple online sources.
**Data Cleaning & Integration:**
- Structured raw stats into Pandas DataFrames.
- Merged multiple sources into one cohesive dataset for use in the simulator.

### 🧩 Object-Oriented Simulation
- Created a Player class (holds player-specific stats, calculates event probabilities).
- Designed a BaseRunners class to track runner advancement, outs, and scoring.
- Built functions to simulate:
  - Lineups facing left- or right-handed pitchers.
  - Custom scenarios (e.g., innings, lineup start spot, base/out states).

### 📊 Scenario Analysis
- Investigated **“Should a team sacrifice bunt in extra innings?”**
  - Simulated thousands of games under two conditions:
    - Runner on 2nd, 0 outs
    - Runner on 3rd, 1 out
  - Compared expected run production between the two strategies.
- Results were visualized with Matplotlib and NumPy to make insights intuitive.

### 🤖 Lineup Optimization
- Implemented two approaches to find the optimal batting order:
  - **Brute force search** (small rosters).
  - **Genetic Algorithm (GA)** for scalable optimization:
    - Population generation, elitism, crossover, and mutation.
    - Cached fitness scores for efficiency.
    - Tuned GA hyperparameters for convergence and exploration balance.
