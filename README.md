# Machine Learning Task: Sales/Demand Forecasting

## About the Task
This task involves predicting future sales using historical business data.  
Sales forecasting helps businesses plan inventory, manage cash flow, and make staffing decisions.  
The focus is on applying machine learning techniques and presenting results in a business-friendly way.

---

## Objective
- Predict future sales/demand using past data.  
- Analyze trends and seasonality.  
- Provide insights that can help in business planning.

---

## Task Checklist

| Task Requirement                     | Status   | Notes                                  |
|-------------------------------------|---------|---------------------------------------|
| Clean & prepare historical data      | ✔ DONE | CSV loaded, date fixed, sorted, columns checked |
| Create time-based features           | ✔ DONE | Year, Month, seasonality added        |
| Apply forecasting techniques         | ✔ DONE | Linear Regression used for prediction |
| Evaluate model performance           | ✔ DONE | MAE & RMSE calculated (RMSE = 497128.01) |
| Visualize forecasts                  | ✔ DONE | Line graph of Actual vs Predicted     |
| Explain trends & business relevance  | ✔ READY | Seasonal patterns identified; helps business planning |
| Tools used                           | ✔ MATCHED | Python, Jupyter Notebook, Pandas, NumPy, Scikit-learn, Matplotlib |

---

## Tools & Libraries
- **Programming & IDE:** Python, Jupyter Notebook / VS Code  
- **Data Handling:** Pandas, NumPy  
- **Machine Learning:** Scikit-learn  
- **Visualization:** Matplotlib  

---

## Steps Performed
1. Load and clean historical sales data.  
2. Convert date column to datetime & create Year/Month features.  
3. Train Linear Regression model for forecasting.  
4. Generate predictions (`y_pred`) for future sales.  
5. Evaluate model using MAE & RMSE.  
6. Visualize Actual vs Predicted sales.  
7. Analyze trends and seasonality for business relevance.

---

## Results & Insights
- Month-wise sales trends identified.  
- Seasonal demand patterns visible.  
- Helps plan inventory and staffing for high/low sales periods.  

---

## Author
**Name:** Sanika Nakade  
**Role:** ML Intern 
