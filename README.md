# __PyBer Analysis__
PyBer_Analysis workspace.
## __Overview of PyBer analysis__
The purpose of this analysis was to see trends in PyBer's ride-share data and to see how different variables affected the profit margins of total fares. The main variable we were comparing and contrasting were different city types which include urban, suburban, and rural. 
## __Results of the analysis__

![Data table for pyber](https://github.com/ChristopheGarcia1/PyBer_Analysis/blob/main/analysis/Data_frame_Pyber.png)


The results of the ride-share data revealed the following underlying trends.

* Through Jupyter notebook the following code was used to find the total rides by city and a refactored code for drivers was also made to find. It was found that the total drivers exceeded the amount of total amount of rides in urban cities meaning that many drivers did not have rides.

          '''Pandas 
          # Get the total rides for each city type
          total_rides_by_type = pyber_data_df.groupby(["type"]).count()["ride_id"]

          # Get the total drivers for each city type
          total_drivers_by_type = city_data_df.groupby(["type"]).sum()["driver_count"]

* While the average fares per driver and ride were higher in rural cities, the overall total fares were the lowest when it came to total fares of suburban and urban cities. 

* Based on the above city types, the relationship between total fares and size of the city have an inverse relationship when it comes to total fares. The more compact city types had more less fares.

## __Summary__

![Line graph of total fares by city type](https://github.com/ChristopheGarcia1/PyBer_Analysis/blob/main/analysis/Fig8.png)

1. With Urban cities having more drivers than rides in the span of 4 month, it is recommended that certian incentives are given to riders of higher populated areas to utilize the excess of drivers that are not given rides.

2. Total fares have an increase in weeks where there are holidays associated with them so marketing for PyBer should push for designated rides for holidays.

3. When we change the sum_of_fares_by_week script to look at days, we can see that weekends are when demand for drivers go up so business can be improved by establishing a perk point system  where people get more points on weekends.

4. Rural cities lack clients and fares are higher, so PyBer could offer discounts when their fares exceed a certain amount since they already are pretty high when compared to other cities. PyBer could increase marketing int hese areas.