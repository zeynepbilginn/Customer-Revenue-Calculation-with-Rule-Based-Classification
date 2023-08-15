# Customer Revenue Calculation with Rule Based Classification  
## Business Problem & Problem  

I wants to create advanced-based (level-based) new sales definitions by using some features of the sales made by Gezinomi and to create segments according to these new sales definitions and to estimate how much the new general general company can earn on average according to these segments.
for example:
It is desired to determine how much an All Inclusive restriction from Antalya can earn on an average during a busy period.  

## Dataset Story
Gezinomi_miuul.xlsx dataset contains the prices of the sales made by Gezinomi company and the information about these sales. The data set consists of records created in each sales transaction. This means that the table is not deduplicated. In other words, the customer may have made more than one purchase.  


## Variables
⚫︎ SaleId : Sales ID
⚫︎ Sale Date : Sale Date
⚫︎ CheckInDate : Customer's login date
⚫︎ Price : Price paid for sale
⚫︎ ConceptName: Hotel concept information
⚫︎ SaleCityName: City where the hotel is located CInDay: The day the customer arrives at the hotel
⚫︎ SaleCheckInDayDiff: Day difference between check-in and check-in Season: Season information on check-in date  

## Libraries
Pandas, matplotlib 
