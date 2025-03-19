# PowerBI_Dashboard_for_Blinkit
**Overview**
This Power BI dashboard provides a comprehensive analysis of sales, marketing, customer engagement, and inventory performance for Blinkit. The data is sourced from Kaggle datasets and integrated using MySQL, allowing real-time insights for better decision-making.

![Screenshot (60)](https://github.com/user-attachments/assets/f643a593-b99d-44a6-bf0a-debf05ac1fba)
![Screenshot (61)](https://github.com/user-attachments/assets/588a4f05-52d4-4c25-bce3-a4431ddcafdd)
![Screenshot (62)](https://github.com/user-attachments/assets/7bbb912f-41e2-4839-853e-8964bfb8ec2f)
![Screenshot (63)](https://github.com/user-attachments/assets/8e75e1ae-28bd-4534-bf31-12c4903e52d1)
![Screenshot (64)](https://github.com/user-attachments/assets/88fabce6-f257-45a0-a662-0c8c9b484ffb)
![Screenshot (65)](https://github.com/user-attachments/assets/af1abd8f-37d0-4a5b-8bf1-131d25e4e897)
![Screenshot (66)](https://github.com/user-attachments/assets/51480461-464c-4743-b00b-017cbbe402ff)


**Setup & Data Integration**
The dashboard is powered by Power BI and connected to MySQL using the ODBC Connector.

**Steps to Set Up:**
Install MySQL and create a database.
Import Kaggle datasets into MySQL using structured tables.
Configure the MySQL ODBC Connector for Power BI.
Use Power Query to clean, transform, and structure data.
Build interactive visualizations and define key metrics.

**Key Features & Metrics**
Sales Overview: Year-over-year growth, conversion rates, revenue insights.
Marketing Performance: Clicks, impressions, ad spend, and ROAS.
Customer Insights: Active users, segmentation, and sales contributions.
Inventory Management: Stock availability, damaged stock percentage.
Feedback Analysis: Customer reviews and sentiment scoring.

**Interactive Filter Panel**
Date Range Selection: Filter data by Last Month, YTD, Last 6 Months, etc.
Multi-Level Filtering: Analyze by area, product name, customer segment.
Metric Switcher: Toggle between Quantity & Value for deeper insights.

**Key Insights**
-6.87% decline in YoY sales suggests the need for improved strategies.
71.83% stock available, but 16.76% is damaged, requiring supply chain optimization.
Strong customer engagement with high conversion rates.
Marketing effectiveness needs improvement based on click-through and impression trends.

**Project Structure**
Blinkit-Dashboard  
│-- Data (Kaggle datasets)  
│-- SQL_Scripts (Database setup scripts)  
│-- PowerBI_Files (PBIX Dashboard file)
│-- DAX csv File 
│-- README.md (Project Documentation)  


**How to Use**
Clone the repository:
git clone https://github.com/your-username/blinkit-powerbi-dashboard.git
Import the SQL scripts into MySQL.
Open Power BI and connect to the MySQL database.
Load and refresh the dashboard to explore insights.
Refer to the DAX expressions in my CSV file 

