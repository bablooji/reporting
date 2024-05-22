# CITI RIDE REPORTING ASSIGNMENT

#### Reporting Tool = Tableau Public Edition 2024.1.2 Mac
#### Reporting file name = BPCITI2023RideDataAnalysis

## DATA SOURCE & GATHERING
#### DATA Source WebSite = https://citibikenyc.com/system-data
#### DATA Used for the project = Jersey City CITI Bike Data
#### Period of Data Used = January 2023
#### Name of the Datafile = JC-202301-citibike-tripdata
#### Format of the Datafile = CSV


## DATA PREPARATION
### Formatted the date columns to be DATATIME

## ADDED CALCULATED FIELDS


#### Start_Month = LEFT(DATENAME('month', [Started At]), 3)
#### Start_hour = DATEPART('hour',[Started At])
#### Start_Day_of_the_Week = DATENAME('weekday',[Started At])
#### start_date = date([Started At])
#### Start_Year = Start_Year

### DASHBOARD 1 - Rides Data Analysis Summary, Added Breakdown by Bike Type indicating electric and classic bike types, Rides Distribution by Membership, And rides per day of the week

#### https://public.tableau.com/app/profile/bhagya.prasad8016/viz/BPCITI2023RideDateAnalysis/RideSummary
#### ANALYSIS - A) About 75% of the riders are members of CITI BIKE
#### ANALYSIS - B) The number of classic bike rides are significantly higher than the electric bikes.
#### ANALYSIS - C) Number of rides over the week is more or less the same. The number of rides on a Tuesday was higher than any other day of the week.


### DASHBOARD 2 - Rides By Starting Station Ranked High to Low, Added Breakdown by Bike Type indicating electric and classic bike types in the mix
#### URL = https://public.tableau.com/app/profile/bhagya.prasad8016/viz/BPCITI2023RideByStation/RideByStation?publish=yes
#### ANALYSIS - Grove Street and Hoboken Station are the two starting points in Jersey City, NJ. 
#### Even though, the top 10 Starting Stations use electric bikes, NEWPORT PATH station does not have any electric bike usage in the month of January 2023.

### DASHBOARD 3 - Rides By Growth, Breakdown by Bike type and membership type
#### URL = https://public.tableau.com/app/profile/bhagya.prasad8016/viz/BPCITI2023RideGrowth/Growth?publish=yes
#### Percentage Ride Growth Chart shows that the rides grown is fairly consistent throughout the month of January 2023.
#### However, on handful no of days of the month shows very high increase in rides and significant drop on a couple of days.
#### As per the breakdown by the bike type and membership types, the rides using electric bikes seems the same throughout the month.
#### But the classic bike ride growth soared on a couple of occassions.


### DASHBOARD 4 - Rides Start and End Location Maps, And Ride by End Station

#### URL = https://public.tableau.com/app/profile/bhagya.prasad8016/viz/BPCITI2023RideMaps/RideMaps?publish=yes
#### Plotted the maps to show the ride density per location (based on the lat and long) data provide for the month of January 2024.
#### I  was able to create the start and end location co-ordinates but for some reason the base map does not show when I merge the two frames

![image](https://github.com/bablooji/reporting/assets/65581001/204eae36-0bbd-4c7b-906b-f5ee0ff222f5)


