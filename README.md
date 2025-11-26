Budget Tracking & Forecasting Model

For my captstone project, my specific role is to create a budget tracking system that predicts whether a user will end the month over or under budget. The project includes a simple database schema, synthetic datasets (budgets + transactions), and a machine learning model that forecasts end-of-month spending based on historical behavior.

This repository contains the data, preprocessing steps, and ML model used for forecasting.


📌 Features

Budget & Transaction Dataset
Synthetic, student-centered spending data aligned with real-world transaction behavior.

Data Engineering
Cleaned and merged budget and transaction data with relationships via budget_id.

Spending Progress Calculation
Automatically computes:

total spent per budget

percent of budget used

category-level aggregations


Forecasting Model
A regression-based model that predicts:

total expected spending by end of timeframe

projected amount over/under budget

forecast line for UI visualization
