## MGS-4701-01
# Capstone Project: Store Sales Forecasting

#### Team: Lina Larrotta & Joceline Guerra

![image](https://github.com/user-attachments/assets/39b29809-76ba-48f2-b216-7157e005191b)

## Introduction
In the fast-paced retail industry, businesses must navigate dynamic market conditions and evolving customer demands. Efficient inventory management and accurate demand forecasting are critical to success, yet traditional methods often fall short in addressing the complexity of sales data. This project leverages the superstore dataset—rich with variables like product categories, sales regions, and customer segments—and employs machine learning to provide actionable insights into sales patterns and demand trends. By addressing common challenges such as overstocking, understocking, and inefficiencies in planning, the project aims to develop a robust predictive model that empowers retailers to optimize inventory, meet customer needs, and enhance operational efficiency, ultimately fostering strategic decision-making and sustained growth.

## Methodology
### Exploratory Data Analysis (EDA):
  - Analyzed trends across product categories, regions, and time periods using Matplotlib and Seaborn visualizations (e.g., bar charts, pie charts, line graphs).
  - Key insights include identifying top-performing regions, seasonal sales trends, and the impact of discounts on profitability.
### Model Development:
  - LightGBM: Efficiently handled large datasets and complex interactions; optimized hyperparameters (learning rate, depth, estimators) via Grid Search for better performance.
  - LSTM: Captured temporal dependencies through a sliding window approach, with sequential length and dropout rates fine-tuned to minimize overfitting.

