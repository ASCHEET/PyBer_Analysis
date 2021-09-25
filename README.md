# PyBer_Analysis

## V. Isualize has requested utilizing, Python skills and knowledge of Pandas, to create a summary DataFrame of the ride-sharing data by city type. Then, using Pandas and Matplotlib, create a multiple-line graph that shows the total weekly fares for each city type. 

### Primary analysis required creating a ride sharing summary from the merged city_data.csv and ride_data.csv.  This required the groupby() function within pandas to sort ride fare data by the city type (Urban, Rural, or Suburban) to get 1) total rides within the 'city type', 2) getting the total drivers withing the 'city type', and 3) then summing the fares for each 'city type.'
### After the total number of rides, drivers, and fares for each 'city type' was sorted, it was easy to calculate the Average Fare Per Ride and the Average Fare Per Driver in the below DataFrame
### ![Figure 1 - Summary DataFrame]()
### Secondary analysis required sorting the data so that fares could be analzed based on date and city type.  A pivot table function was used within Pandas that allows the data to be indexed by the date (making it esier to sort/filter) and then assigning the columns to city type, with the values as the fares collected for the ride service performed.
### The data was refined into weekly totals for the dates between January and April of 2019.  The data is shown in DataFrame view below
### ![Figure 2 - weekly_fares]()
### The same fare data is plotted with a line graph for quick visual understanding for each city type voer the first four months of 2019.
### ![Figure A - plot]()





































