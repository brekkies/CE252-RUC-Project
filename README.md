# CE252-RUC-Project
CE 252 RUC Project: Blake Thomas, Ari Gonzalez, Nathan Streater, Archer Gu

## Repository contains all data used and the data analysis python code. 

hhv2pub.csv : Household level data (source for income)     Source: 2022 National Household Travel Survey

vehv2pub.csv : Vehicle data (source for vehicle type, fueltype, year. Joined to household data)     Source: 2022 National Household Travel Survey

table_export.csv : Fuel efficiency data by vehicle type,  year    Source: EPA https://www.epa.gov/automotive-trends/explore-automotive-trends-data#DetailedData

vehicles.csv : Other vehicle data, not used in final code


# Python code summary: 

  First, join vehicle data to household data and group by income. Find the proportion of each vehicle/fuel type within each income group. Final result is 'df'
  
  Next, import and clean fuel economy data. Find the average gallon per mile (GPM) for each vehicle/fuel type. Then find the average GPM for combinations of vehicle year and type
  
  Next, use fuel economy averages to find the expected GPM for each income group
  
  Next, find the tax per mile assuming current CA fuel tax level
  
  Next, find the change in tax under RUC assuming the a per-mile charge equal to the average tax per mile from the previous step
  
  Finally, graph the change in tax
  
  Additionally, graph the change in tax without accounting for vehicle age
