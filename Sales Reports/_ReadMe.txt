#These are sales reports for various brands operating through multiple hubs.
#Each brand has different format of its sales report. 
#Main challenge here is to stage this all data within single table to draw analytics. 
#Master template.xlsx is the universal template to be picked up for staging data to SQL DB. 
#For each brand and hub there are some transformations are executed through python and then it is staged to SQL DB

(Hub)- Hub_id
	1.(Brand1) - Brand1_id
	2.(Brand2) - Brand2_id
...

(ITI)- 01	
	 1. (KIA) - 01  
	 2. (Hyundai) - 02	
	 3. Too Yum - 03
	
(NCK)- 02	
	 1. (OneEight)- 04	
	 2. (Puma)- 05	
	
(RP)- 03	
	 1. (Telcom)- 06		
	 2. (WD)- 07		
	 3. (MCD)- 08	 
	 4. (KFC)- 09 	
	 5. (Anega)- 10
	 
(BM)- 04	
	 1. (MCD)- 08	 
	 2. (Airtel)- 11 		
	 3. (Docomo)- 12
	 
(GGN)- 05 	
	 1. (MCD)- 08	 
	 2. (KIA) - 01
