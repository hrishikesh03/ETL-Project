## ETL-Project for EasyB2R (Retail Company)


This is ETL project for retail distribution company (EasyB2R) which operates in various cities and with multiple brands. EasyB2R's primary role is to purchase products from different brands and efficiently deliver them to retailers within each city. To streamline this process, brand salesmen capture orders through their dedicated brand order system.

To ensure accurate and up-to-date information for EasyB2R's analytics needs, it is crucial that they monitor the sales data for all brands on a daily basis. Therefore, I have designed an Extract, Transform, Load (ETL) project that will consolidate and integrate the brand sales reports into SQL DB. By effectively analyzing the sales data, we can identify trends, optimize inventory management, and make informed decisions to propel our business growth.

This ETL code is designed to streamline the process of picking sales report from each brand and hub and Performs necessary transformations, and stages the data into a SQL database. This staged data serves as a reliable source for generating Power BI Dashboards, providing valuable insights for decision-making purposes.

In addition to its core functionalities, the ETL code also performs data validation checks. It verifies the record counts received from each brand, ensuring accuracy and consistency in the data being processed. Furthermore, it validates the record counts staged into the SQL database, guaranteeing data integrity throughout the entire pipeline.

Once all operations are completed successfully, this ETL code generates an upload report summarizing the entire process.
Here are two key features of Upload Reports:

1. Record count validation check: The report includes a comparison between the record count in the received file and the loaded record count in the database. This validation check helps us identify any discrepancies or potential errors during the data staging process.

2. File received flag for tracking missing Sales reports: The report also contains a "File received" flag, which allows us to track which hubs and brands are missing Sales reports. This information helps us proactively address any gaps in our sales reporting.

By leveraging this ETL code and the underlying data lake, I have prepared a highly informative Dashboard that gives a complete overview of the business. Some key features of the Dashboard include:

1. Brandwise Sales Analysis: Gain insights into individual brand performance, identify trends, and make informed decisions to drive growth.

2. Retailer Analysis: Evaluate retailer performance based on sales data, identify top-performing retailers, repeat order ratio.

3. Sales Target Achievement: Monitor how well your sales teams are achieving their targets and track progress towards set goals.
