# CITI RIDE REPORTING ASSIGNMENT

## Reporting Tool = Tableau 
## DATA Source WebSite = https://citibikenyc.com/system-data
## DATA Used for the project = Jersey City CITI Bike Data
## Period of Data Used = January 2023
## Name of the Datafile = JC-202301-citibike-tripdata
## Format of the Datafile = CSV


## DATA PREPARATION
## Formatted the date columns to be DATATIME

## ADDED CALCULATED FIELDS


### Start_Month = LEFT(DATENAME('month', [Started At]), 3)
### Start_hour = DATEPART('hour',[Started At])
### Start_Day_of_the_Week = DATENAME('weekday',[Started At])
### start_date = date([Started At])
### Start_Year = Start_Year

### DASHBOARD - Rides By Station Ranked High to Low, Added Breakdown by Bike Type indicating electric and classic bike types in the mix
#### URL = https://public.tableau.com/app/profile/bhagya.prasad8016/viz/BPCITI2023RideByStation/RideByStation?publish=yes
#### ANALYSIS

https://public.tableau.com/app/profile/bhagya.prasad8016/viz/BPCITI2023RideDateAnalysis/RideSummary

https://public.tableau.com/app/profile/bhagya.prasad8016/viz/BPCITI2023RideGrowth/Growth?publish=yes

https://public.tableau.com/app/profile/bhagya.prasad8016/viz/BPCITI2023RideMaps/RideMaps?publish=yes



