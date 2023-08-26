# Income-Statement-Lululemon
Financial Analysis Toolkit: Python code for income statements, ratios, break-even, EPS trends, and sensitivity analysis. Gain insights into company performance and make informed decisions.

This README document provides an overview of the code and its functionalities for conducting financial analysis related to a company's income statement, profitability ratios, break-even analysis, earnings per share (EPS) trends, and sensitivity analysis. The code is written in Python and utilizes various libraries for data analysis and visualization.

Table of Contents: 
1. Libraries and Data Loading
2. Sankey Diagram
3. Profitability Ratio Analysis
4. Break-Even Analysis
5. Earnings Per Share (EPS) Trends Analysis
6. Sensitivity Analysis

Libraries and Data Loading: 
This section of the code imports necessary libraries including numpy, pandas, seaborn, matplotlib, plotly.graph_objects, warnings, and yfinance. These libraries are used for data manipulation, visualization, and fetching historical stock price data. The code loads data from an Excel file using the openpyxl library.

Sankey Diagram: 
The Sankey diagram section of the code visualizes data related to financial flows within a company, showing how various financial categories are interconnected. It uses the plotly.graph_objects library to create the diagram, using data manually loaded from an income statement data dictionary.

Profitability Ratio Analysis: 
In this section, the code calculates profitability ratios such as gross profit margin, operating profit margin, and net profit margin. It uses pandas to organize income statement data and perform calculations. The profitability ratios are then compared to industry benchmark ratios to assess the company's financial health and competitiveness.

Break-Even Analysis: 
The break-even analysis section calculates the break-even point, which is the level of sales at which total revenue equals total costs, resulting in no profit or loss. It calculates the break-even point based on fixed costs, variable costs per unit, and selling price per unit.

Earnings Per Share (EPS) Trends Analysis: 
This section analyzes the company's earnings per share (EPS) over time and compares it with stock price data. The code fetches historical stock price data using the yfinance library and combines it with manually provided EPS data. The results are visualized using matplotlib to show trends in EPS and stock prices over the years.

Sensitivity Analysis: 
The sensitivity analysis section assesses the impact of changes in key variables (sales volume, selling price, and variable costs) on the company's net income. It uses nested loops to iterate through different scenarios and calculates net income based on varying variables. The results are stored in a pandas DataFrame and visualized using scatter plots.

Please note that this README provides a high-level overview of the code's functionalities and sections. For detailed explanations and code implementation, refer to the actual code file.
