🛒 Time Series Forecasting

📂 Project Structure  
├── README.md  
├── Walmart_Sales.ipynb              # Forecasting weekly sales at the store/chain level  
├── Vegetable_Price_Dataset.ipynb    # Forecasting SKU demand under price increases  


📌 Project 1: Walmart Sales Forecasting (Walmart_Sales.ipynb)

Objective: Forecast weekly sales to support inventory and staffing decisions.

Highlights:

- Applied outlier detection (Winsorizing & 3σ clipping) to stabilize noisy sales data

- Explored trends & seasonality using moving averages & decomposition

- Forecasted sales with Exponential Smoothing, Holt’s Linear Trend, Holt-Winters Seasonal

- Benchmarked with XGBoost Regressor + hyperparameter tuning (RandomizedSearchCV)

- Evaluated using MAE, RMSE, Bias

📌 Project 2: SKU Price Increase Forecasting (Vegetable_Price_Dataset.ipynb)

Objective: Forecast the effect of price changes on SKU-level demand to inform pricing strategy.

Highlights:

- Engineered features capturing historical price, promotions, and demand elasticity

- Applied regression & tree-based models (XGBoost) to predict demand under new prices

- Used cross-validation to ensure robust forecasts

- Delivered insights into price sensitivity and optimal pricing strategies

- Generated SKU-level forecast plots for different price increase scenarios

⚙️ Technical Skills Demonstrated

- Time Series Analysis & Forecasting

- Feature Engineering for Price Elasticity Modeling

- Machine Learning with XGBoost (RandomizedSearchCV, hyperparameter tuning)

- Evaluation Metrics: MAE, RMSE, Bias

- Visualization: Forecast & price-demand response curves

🛠️ Tech Stack

Python

Libraries: pandas, numpy, matplotlib, seaborn, statsmodels, sklearn, xgboost
