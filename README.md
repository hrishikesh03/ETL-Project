## ETL-Project for EasyB2R (Retail Company)


This is ETL project for retail distribution company (EasyB2R) which operates in various cities and with multiple brands. EasyB2R's primary role is to purchase products from different brands and efficiently deliver them to retailers within each city. To streamline this process, brand salesmen capture orders through their dedicated brand order system.

To ensure accurate and up-to-date information for EasyB2R's analytics needs, it is crucial that they monitor the sales data for all brands on a daily basis. Therefore, I have designed an Extract, Transform, Load (ETL) project that will consolidate and integrate the brand sales reports into SQL DB. By effectively analyzing the sales data, we can identify trends, optimize inventory management, and make informed decisions to propel our business growth.

This ETL code is designed to streamline the process of picking sales report from each brand and hub and Performs necessary transformations, and stages the data into a SQL database. This staged data serves as a reliable source for generating Power BI Dashboards, providing valuable insights for decision-making purposes.

In addition to its core functionalities, the ETL code also performs data validation checks. It verifies the record counts received from each brand, ensuring accuracy and consistency in the data being processed. Furthermore, it validates the record counts staged into the SQL database, guaranteeing data integrity throughout the entire pipeline.

Once all operations are completed successfully, this ETL code generates an upload report summarizing the entire process.


