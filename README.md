# Retail Dynamic Pricing using Reinforcement Learning

<p align="left">
  <img src="https://img.shields.io/badge/STATUS-EDUCATIONAL%20PROJECT-0078D4?style=for-the-badge" />
  <img src="https://img.shields.io/badge/ALGORITHM-Q--LEARNING%20|%20DQN-E87B1E?style=for-the-badge" />
  <img src="https://img.shields.io/badge/DOMAIN-RETAIL%20OPTIMIZATION-606060?style=for-the-badge" />
</p>

<p align="left">
  <img src="https://img.shields.io/badge/ENVIRONMENT-GYM%20|%20CUSTOM%20SIM-555555?style=for-the-badge" />
  <img src="https://img.shields.io/badge/STACK-PYTHON%20|%20PYTORCH-0078D4?style=for-the-badge" />
</p>

> **An intelligent pricing engine that utilizes Reinforcement Learning to dynamically adjust product prices in real-time, maximizing revenue and inventory turnover by learning from consumer demand patterns and market competition.**
## Project Overview
This project implements a Reinforcement Learning (RL) agent to solve the classic business challenge of Dynamic Pricing. By utilizing a Q-Learning algorithm, the agent learns to adjust product prices ($60, $70, or 80) based on current Inventory Levels to maximize total revenue.

The project simulates a real-world retail environment where lower prices drive higher demand, but higher prices increase margins, requiring the agent to find the optimal balance over 1,000 training episodes.

## Technical Stack

* **Language:** Python
* **Libraries:** pandas, numpy, matplotlib
* **Algorithms:** Q-Learning (Reinforcement Learning)
* **Data Source:** Retail Store Inventory and Demand Forecasting Dataset (Kaggle)

## Key Features

* **Data Preprocessing:** Cleaning and filtering large-scale retail data (76,000 rows) for specific product analysis.
* **Discretization:** Converting continuous inventory levels into discrete states (0 to 250 units) for the Q-Table.
* **ϵ-greedy Strategy:** Implementing a balance between exploration (trying new prices) and exploitation (using learned best prices).
* **Simulation Engine:** A custom function that models demand elasticity relative to price points.
* **Visualization:** Performance tracking through Reward-per-Episode curves and Q-Table heatmaps.

## Results

The agent successfully converges toward an optimal pricing policy. The final Q-Table Heatmap provides a visual representation of the "value" of taking specific pricing actions at different stock levels, helping stakeholders understand AI-driven decision-making.

## Project Structure

```Plaintext
├── ParRenforcement.ipynb   # Main Jupyter Notebook with RL implementation
├── sales\_data.csv          # Retail dataset (from Kaggle)
└── README.md               # Project documentation
```
