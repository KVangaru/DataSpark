# DataSpark
****Illumination insights for Global Electronics
Problem Statement:
As part of Global Electronics' data analytics team, you are tasked with conducting a comprehensive Exploratory Data Analysis (EDA) to uncover valuable insights from the company’s data. Your goal is to provide actionable recommendations that can enhance customer satisfaction, optimize operations, and drive overall business growth.
Global Electronics, a leading retailer of consumer electronics, has provided you with several datasets containing information about their customers, products, sales, stores, and currency exchange rates. The company seeks to leverage this data to better understand their business and identify areas for improvement.
Approach:
Data Cleaning and Preparation
Checked for missing values and handled them appropriately. Converted the data types where necessary (e.g., dates, numerical values). Merged the datasets where necessary for analysis (e.g., linking sales data with product and customer data).
Loaded the data and insert the preprocessed data into an MySQL database from Python (Visual Source) for each data source.
Power BI Visualization: Connected SQL to Power BI, imported the data, and created interactive dashboards.
This project contains the actual data sets in csv format(Customers, Products, Stores, Sales, Exchange Rates), the .ipynb file which has the data cleaning and preparation steps including loading data into MySQL from Python. 
You may have to change the .ipynb file with your connection string to MySQL and your password for your user (for example 'root' user). This steps loads the data into MySQL database.
You can import DataSpark_PBI report to your PowerBI to view the insights into the reports.
Finally this project contains the file 'Global Electronics Data Insights' that analyses customers, sales performance, products, stores and the recommendations.
