\# Retail Dynamic Pricing \& Inventory Optimization (Q-Learning)

\## 📊 Project Overview



This project implements a Reinforcement Learning (RL) agent to solve the classic business challenge of Dynamic Pricing. By utilizing a Q-Learning algorithm, the agent learns to adjust product prices ($60, $70, or 80) based on current Inventory Levels to maximize total revenue.



The project simulates a real-world retail environment where lower prices drive higher demand, but higher prices increase margins, requiring the agent to find the optimal balance over 1,000 training episodes.

\## 🛠️ Technical Stack

* \*\*Language:\*\* Python
* \*\*Libraries:\*\* pandas, numpy, matplotlib
* \*\*Algorithms:\*\* Q-Learning (Reinforcement Learning)
* \*\*Data Source:\*\* Retail Store Inventory and Demand Forecasting Dataset (Kaggle)



\## 🚀 Key Features

* \*\*Data Preprocessing:\*\* Cleaning and filtering large-scale retail data (76,000 rows) for specific product analysis.
* \*\*Discretization:\*\* Converting continuous inventory levels into discrete states (0 to 250 units) for the Q-Table.
* \*\*ϵ-greedy Strategy:\*\* Implementing a balance between exploration (trying new prices) and exploitation (using learned best prices).
* \*\*Simulation Engine:\*\* A custom function that models demand elasticity relative to price points.
* \*\*Visualization:\*\* Performance tracking through Reward-per-Episode curves and Q-Table heatmaps.



\## 📈 Results



The agent successfully converges toward an optimal pricing policy. The final Q-Table Heatmap provides a visual representation of the "value" of taking specific pricing actions at different stock levels, helping stakeholders understand AI-driven decision-making.

\## 📂 Project Structure



```Plaintext



├── ParRenforcement.ipynb   # Main Jupyter Notebook with RL implementation

├── sales\_data.csv          # Retail dataset (from Kaggle)

└── README.md               # Project documentation

```

