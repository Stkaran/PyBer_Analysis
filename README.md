# PyBer_Analysis

## Overview
For this assignment, we were tasked with creating a new dataframe from our ride share data to more closely inspect the differences in ride fares based on the different city types we had: Urban, Suburban, and Rural. In doing this, we to hope to find where there are issues with the service and how they might be addressed. 


## Results
     	    Total Rides 	Total Drivers 	Total Fares 	Average Fare per Ride 	Average Fare per Driver
    Rural 	      125 	          78 	          $4,327.93 	        $34.62 	                  $55.49
    Suburban      625 	         490 	          $19,356.33 	        $30.97 	                  $39.50
    Urban 	      1,625 	       2,405 	          $39,854.38 	        $24.53 	                  $16.57

Above is the summary of data in our new dataframe. Unsuprisingly, the urban areas had the highest amount of both rides and drivers due to their populations. We can also see that as the number of drivers increases, the fare of the rides decrease. The rural areas demonstrate the opposite scenario perfectly: fewer drivers equals higher cost for rides. A simple issue of supply and demand. The problem here is that if this trend continues, if will be difficult to expand usage of the Pyber service as the high costs will deter more customers from using Pyber, and it will be hard to get new drivers if they don't have any customers to drive. 

![image](https://github.com/Stkaran/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)

Our chart shows us that across the months of January through April, no city type had a spike in profits or demand when compared to the others. The main factor behind higher fare values is population count and since Pyber cannot magically increase rural area's population, we nust develop incentives to increase engagement in these less populated areas.

## Recommendations 
Starting with the rural areas, it will be important to have a more targeted plan to keep and increase to rider base. This begins with communicating with the few drivers that are in the area and hearing from them what the most common destinations and type of customer they usually get. By doing this we can help them promote their services more effectively.

For urban areas, the prior recommendation is obviously not feasible with the shear amount of drivers they have. In order to increase revenue here, it is important tailor the fares based when there is highest demand during the week. For example, there will almost always be more customers during evenings (getting home from work, going to dinner, etc.) and even more so during weekends. 

Suburban areas are trickiest areas. In many urban areas, much of the population won't own a car and therefore drive up demand, however this won't always be the case in suburbs. The important part here is to focus on convenience and making Pyber more appealing than taking your own car. One option could be to offer rewards for recurrent ridership (discount, gift cards) in order make people feel like they are getting more out of Pyber's services than just doing things themselves. 
