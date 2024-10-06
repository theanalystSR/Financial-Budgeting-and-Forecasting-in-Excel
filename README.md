Financial Budgeting and Forecasting in Excel
This project demonstrates a simple approach to financial budgeting and forecasting using Excel and Python. The repository includes:

Historical financial data in CSV format
A budget template for forecasting future revenues, costs, and profits
Python code to automate forecasting and generate new budget data
Visualization of actual vs. forecasted values using Excel charts
Features
CSV Data Files:

Historical_Sales.csv: Contains historical sales data (revenue, cost, and profit).
Budget_Template.csv: A blank template to forecast the next 12 months' budget.
Forecasting:

Python code applies simple percentage growth to forecast future revenue and cost.
Profit is calculated as the difference between revenue and cost.
Excel Visualization:

The output Excel file includes line charts comparing actual and forecasted values for revenue, cost, and profit.
Files
Historical_Sales.csv
Historical sales data for 12 months, including columns for:

Month
Revenue
Cost
Profit
Budget_Template.csv
A template with placeholders to forecast revenue, cost, and profit for the next 12 months.

Forecasted_Budget_with_Charts.xlsx
The final Excel file with forecasted values and visualizations:

Revenue Forecast vs Actual (line chart)
Cost Forecast vs Actual (line chart)
Profit Forecast vs Actual (line chart)
Getting Started
Prerequisites
Python 3.x
Libraries: pandas, openpyxl, matplotlib
Install the required Python packages:

bash
Copy code
pip install pandas openpyxl matplotlib
Running the Code
Clone this repository:
bash
Copy code
git clone https://github.com/your-username/financial-budgeting-forecasting.git
cd financial-budgeting-forecasting
Ensure the CSV files (Historical_Sales.csv and Budget_Template.csv) are in the same directory as the Python code.

Run the Python script to generate the forecasted budget and export to Excel:

bash
Copy code
python forecast_budget.py
Open the generated Forecasted_Budget_with_Charts.xlsx file to see the forecast data and charts.
Visualizations
Revenue Forecast vs. Actual

Cost Forecast vs. Actual

Profit Forecast vs. Actual

License
This project is licensed under the MIT License - see the LICENSE file for details.
