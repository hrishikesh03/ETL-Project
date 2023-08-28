## ETL-Project for EasyB2R (Retail Company)


This is ETL project for retail distribution company (EasyB2R) which operates in various cities and with multiple brands. It buys products from various Brands and delivers them to the retailers in the city.
Orders are captured by Brand's salesman through brand order system. 
The brand sales report is generated on daily basis. Distribution company(EasyB2R) mentains its inventory for each brand accordingly. 

For EasyB2R's Analytics purpose, It becomes very critical to monitor the sales data for all the Brands on frequent basis. Cleaning each brand file and extracting datapoints mannually on daily basis and visualize the business is bit hectic task. Thats where the probelm arises.

This project simplifies the ETL process. It picks all brand reports from each hub, executes necessary transformations and stages data to SQL DB which is further being used for Power BI Dashboards.  

It also validates the reord counts received from brands, record counts staged into DB. It generates upload report once its finishes executing. It also flags brands and hubs whose sales reports are not received.
