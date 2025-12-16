# AI Sales Forecasting using Machine Learning

# Project Overview
This project demonstrates an end-to-end machine learning approach to forecasting retail sales using historical transaction data. The goal is to predict future monthly sales to support business planning, budgeting and decision-making.

The project covers data preparation, feature engineering, model training, evaluation and forecasting using Python and scikit-learn.


# Dataset
- Source: Superstore Sales Dataset (Kaggle)
- Type: Retail transaction data
- Target variable: Monthly Sales
- Time range: Multiple years of historical sales data

# Tools and Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab


# Methodology
1. Data loading and cleaning  
2. Monthly sales aggregation  
3. Exploratory Data Analysis (EDA)  
4. Feature engineering using time-based variables  
5. Model training:
   - Linear Regression (baseline)
   - Random Forest Regressor  
6. Model evaluation using MAE, RMSE, and R²  
7. Forecasting sales for the next six months  


# Results
- Linear Regression achieved better performance than Random Forest on this dataset due to the linear nature of time-based trends.
- The final model successfully captured long-term sales patterns and seasonality.
- Six-month sales forecasts were generated to provide forward-looking business insights.

# Project Structure
AI-Sales-Forecasting
  data
 1. monthly_sales.csv
 2. model_comparison_results.csv
 3. sales_forecast_next_6_months.csv

notebooks
  1. Sales_Forecasting_Project.ipynb

models
 1. linear_regression_model.pkl
README.md
requirements.txt


# How to Run the Project
1. Clone this repository  
2. Install dependencies from `requirements.txt`  
3. Open the notebook in Jupyter or Google Colab  
4. Run the notebook cells sequentially  


# Key Takeaways
- Simple models can outperform complex ones when data patterns are largely linear.
- Time-based feature engineering is critical for forecasting tasks.
- Machine learning can provide actionable insights for business decision-making.


# Author
Paul Adeniyi Adesina 
MSc – Applied Artificial Intelligence & Data Analytics
Data Scientist/Analyst/ Aspiring Global Talent Visa Applicant  
GitHub: https://github.com/Paul-Adeniyi
LinkedIn: https://linkedin.com/in/paul-adeniyi-138b4b243

# Data Source
The dataset used in this project is the Superstore Sales Dataset, publicly available on Kaggle:
https://www.kaggle.com/datasets/vivek468/superstore-dataset-final

# Project Significance
This project demonstrates the practical application of machine learning to a real-world business problem. Rather than focusing solely on model complexity, the project emphasises thoughtful feature engineering, model evaluation and clear interpretation of results.

It highlights how even simple models, when applied appropriately can generate valuable insights and support informed decision-making in areas such as sales planning, budgeting and inventory management.

# Future Improvements
Potential enhancements to this project include:

- Incorporating lag-based features (e.g., previous month sales, rolling averages)
- Exploring advanced time-series models such as Prophet or ARIMA
- Evaluating external factors such as promotions or holidays
- Building an interactive dashboard using Power BI or Tableau
- Deploying the model as a simple forecasting API

These improvements could further enhance forecasting accuracy and business usability.




