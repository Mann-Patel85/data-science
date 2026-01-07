# Retail Data Cleaning & Analysis Pipeline

## 📌 Project Overview
This project simulates a real-world data engineering task. It takes a raw, corrupted string of retail sales data (simulating a messy log file), cleans it using **Basic Python**, and then performs statistical analysis using **Pandas** and **NumPy**.

## 🚀 Key Features
* **Data Cleaning (Basic Python):**
    * Parses raw text data without external libraries.
    * Handles string manipulation (stripping whitespace, fixing capitalization).
    * Logic to handle and remove missing values ('?').
    * Converts currency strings to usable integers.
* **Data Analysis (Pandas & NumPy):**
    * Calculates Tax calculations based on categorical logic using `np.where`.
    * Aggregates sales performance by Region using Pandas `groupby`.

## 🛠️ Technologies Used
* **Python 3.x** (Core logic)
* **Pandas** (Data aggregation)
* **NumPy** (Vectorized calculations)