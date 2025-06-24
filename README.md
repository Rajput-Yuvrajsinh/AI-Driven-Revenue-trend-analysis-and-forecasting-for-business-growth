📊 AI-Driven Revenue Forecasting and Trend Analysis
A Streamlit-based interactive dashboard for revenue prediction, trend analysis, and business insights using Machine Learning (Random Forest) and Deep Learning (LSTM). This system supports user authentication and role-based access control to deliver personalized analytics for Admins, Managers, and Analysts.

🔍 Project Overview
This application provides real-time forecasting and visualization features based on historical Walmart sales data. It enables organizations to monitor and predict profit trends using advanced machine learning models.

👨‍💻 Developed By
Rajput Yuvrajsinh Shersinh
Intern, Infolabz IT Services Pvt. Ltd.

🎯 Objectives
Build a smart revenue forecasting tool using ML and LSTM.

Provide separate dashboards for Admins, Managers, and Analysts.

Help businesses make informed decisions based on visualized trends and profit forecasts.

⚙️ Features
🔐 User Authentication & Role-Based Access
Signup/Login System using a CSV file for user management.

Roles:

Admin: Full access to Dataset, Dashboard, Prediction, Visualization, Admin Panel.

Manager: Access to Dashboard, Visualization, Project Overview.

Analyst: Access to Dataset, Prediction, Growth Analysis, Visualization.

📁 Dataset Used
Source: Walmart.csv

Columns: date, unit_price, quantity, city, category, payment_method, profit_margin, etc.

📉 Prediction Module
ML Model: Random Forest Regressor

Inputs: unit price, quantity, branch, city, category, payment method

Output: Forecasted profit margin and future revenue (next N days)

📈 Quarterly Forecasting (LSTM)
Predicts profit for the next 90 days

Trained on time-series daily profit data

Uses a 30-day window for sliding predictions

📊 Visualization Dashboard
Revenue metrics (Total, Average Profit Margin)

Filterable by date range

Visuals include:

Bar & Pie charts

Actual vs Predicted trends

Monthly revenue patterns

LSTM-based quarterly forecasts

🧠 Technologies Used
Component	Tools/Libraries
Web App	Streamlit
ML Model	Scikit-learn (RandomForestRegressor)
DL Model	Keras (LSTM), TensorFlow
Visualization	Plotly, Plotly Express
Data Handling	Pandas, NumPy
Auth System	CSV-based persistent login system
