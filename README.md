# Vending Analysis BY Breanna Parker

Background/History: This project includes two datasets, one for the inventory, and one for the restock. This is analyzing the overall use of the vending machines and seeing how much inventory should be ordered on a week by week basis. 

Data Explanation (Data prep/Data dictionary/etc): Dates were expanded on for both to include the day of the week, month, and year to be able to better see the nuances in the fluctuations of inventory. There was no missing data or duplicated data. Graphs were created to look at the total quantity expensed and restocked over time. This was also broken down by month, day of the week, and seasonality. 

Methods: I created a forcast and made a function to run through each sku to see the variability per machine. This was to see if there were any machines that weren't producing good results anymore, or if there was a location where more machines were needed. Each sku was was ran using the ARIMA model in this function. 

Analysis: Overall, this is a good and accurate model for predicting how much someone should order for demand on particular skus. 

Conclusion: There is less and less inventory being bought at all skus. This analysis did what it was supposed to do but now there needs to be additional research into what's causing the decease in sales for several years. 

Assumptions: This is only looking at supply/demand, and not what is going on at a specific location. There was a huge spike in sales on a particular week but there isn't anyway of finding out what casued that. If it was a huge event that just started on a regular basis at a specific location, then that will change the data and we will see a significant increase in sales coming up. 

Limitations: THe biggest limitation is that there isn't data on the location that these vending machines are at. We don't know how the economy is going, if there are busineses closing down or even if the products being offered just aren't popular anymore. There is a lot more research that needs to be done to find out what's going on at these locations. Also, vending machines can be moved. So, there should be more research on the need for vending machines at different locations so that they can be moved for better accessibliity. 

Future Uses/Additional applications: If someone knows that they have good locations and regular events, then this is a good predictor model to see what you might need to order for the following restock. If there is a really big event going on, the company might have to make adjustments but if it's a pretty regular business, then this is very usefuly. 

Ethical Assessment: The only information this data really uses is how much people are buying for restock and to possibly move machines. This could affect people who rely on a particular vending machine for their daily breakfast/lunch and then the company moves it since they're not getting enough traffic. If this is some people's only way to get food at a certain location, then it good nevatively affect them when companies make big decisions simply based on these numbers. 
