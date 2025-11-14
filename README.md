# Supply Chain & Demand Forecasting

## Project Summary
This project focuses on two key areas: **Supply Chain Analytics** and **Demand Forecasting**. The main goal is to use advanced analytics and forecasting techniques to generate actionable insights that improve decision-making in supply chain operations. The demand forecasting component specifically predicts product demand for the upcoming month to guide inventory planning.

## Business Context
Accurate demand forecasting is essential for maintaining the right inventory levels, avoiding stockouts, and preventing overstock. This project tackles the challenge of predicting weekly sales for different store-SKU combinations, helping businesses make data-driven decisions for inventory control and promotional strategies.

## Modeling Approach & Evaluation
The project employs the following models for forecasting demand:

- **MSTL (Multiple Seasonal-Trend decomposition using Loess):** A statistical technique that breaks down time series data into trend, seasonal, and residual components.  
- **TimeGPT:** A generative pre-trained transformer model designed for time series prediction.

**Performance Metrics:**
- Mean Absolute Error (MAE)  
- Symmetric Mean Absolute Percentage Error (SMAPE)  

### Model Performance

<img width="7200" height="2400" alt="errormodels" src="https://github.com/user-attachments/assets/90960ad2-faf6-4a90-83f9-eec295d0d93e" />

MSTL demonstrated higher accuracy and more reliable predictions than TimeGPT, with errors more tightly clustered around zero and fewer extreme deviations.

## Key Takeaways
The forecasting models developed in this project provide clear insights into future product demand, allowing retail managers to make informed inventory decisions. By minimizing stockouts and overstock situations, the model supports cost reduction and better customer satisfaction. Future improvements could include integrating additional variables such as promotions, holidays, and competitor pricing to further refine forecast accuracy.
