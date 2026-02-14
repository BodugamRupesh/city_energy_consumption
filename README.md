# City Energy Consumption Analysis & Prediction System
Project Overview
This project analyzes electricity consumption patterns across city zones and predicts
next-day energy demand using machine learning techniques.
Dataset Info
Contains 1 year of data across 5 zones with temperature, humidity, special events, and
consumption.
How to Generate/Load Dataset
Load using: pd.read_csv(""city_energy_consumption.csv")
How to Run Notebook
Run energy_consumption.ipynb and execute all cells. Use interactive input for
prediction.
Insights
• Summer months had highest usage
• Events increased consumption 15–35%
• Industrial zones had highest baseline usage
• Random Forest achieved better accuracy than Linear Regression
Future Improvements
• Multi-year forecasting
• Weather API integration
• Deep learning models
