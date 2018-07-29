# DailyTradeReportingEngine
Execute Reports of settled incoming and outgoing USD amount of trade in the international market.

1. Check If the Settlement Date is a Working Day ?
	a) If the Currency is "AED" or "SAR", Check if the working day is From Sunday to Thursday
	b) If the Currency is not "AED" or "SAR", Check if the working day is From Monday to Friday
	
2. If it is a working day, 
	a) Calculate the USD Amount of Trade.
	b) Calculate the Incoming and Outgoing trade reports.
		(1)) If it is a S - Sell, then it is an Amount in USD settled incoming
		(11)) If it is a B - Buy, then it is an Amount in USD settled outgoing
			
3. If it is not a working day, change the settlement date to the next working date.
	
4. Calcuate the Rank of Incoming and Outgoing Reports.
	
5. Print the report in system console.
