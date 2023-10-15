
#This is the ETL code to stage all the received Brand sales invoice reports to SQL DB by executing all the necessary transformations.
#It imports required columns from Brand system generated sales report, executes required transformations and stages that data into SQL DB.
#It also generates Upload report which validates Record counts in the received files and Uploaded record count once all received brand reports are uploaded to SQL DB 
#Upload report also highlights the hubs and brands from whom sales reports are not received.
