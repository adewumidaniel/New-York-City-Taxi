# New-York-City-Taxi

### Project Overview

-	This dataset contains 6 tables in csv format, along with a geospatial map in TopoJSON and Shapefile formats 
-	The 4 Taxi Trips tables contain a total of 28 million Green Taxi trips in New York City from 2017 to 2020. Each record represents one trip, with fields containing details about the pick-up/drop-off times and locations, distances, fares, passengers, and more 
- The 454 Calendar table contains a fiscal calendar (2017-2020) used by the Taxi & Limousine Commission, with fields containing the date and fiscal year, quarter, month, and week 
-	The Taxi Zones table contains information about 265 zone locations in New York City, including the location id, borough, and service zone 
- The Taxi Zones Map files contain a map of New York City with divisions for the 265 locations that can be used to create custom map visuals in Power BI (TopoJSON) or Tableau (Shapefile)



![image](https://github.com/user-attachments/assets/9e75913a-eadb-4126-9fdc-afd7ae72eef9)



### Data Sources

Primary dataset used for this analysis is the combination of "taxi_zones.csv", "data_dictionary.csv", "454_calendar.csv", "taxi_zones_map.json", “2018_taxi_trips.csv”,” 2017_taxi_trips.csv”. file from Quantum Analytics NG contained detailed information about New York City Taxi 

### Tools 
- Power Query - Data Cleaning
- Power Query - Data Merging / Modeling
- Creating Appendices
- Power BI- Data Analysis
- Power BI - Create Report

### Data Cleaning/Preparation

In the initial data preparation phase, we performed the following task:

1.	Loading data on Power query
2.	Inspection and aligning 
3.	Creating Appendices
4.	Data cleaning and formatting
5.	Loading data for Analyzing
6.	Create new measures 
7.	Creating Report

### Exploratory Data Analysis

EDA involved exploring the New York City Taxi as:
- What is the amount buy Borough 
- What is the total Amount by zone
- What is the total amount buy payment type
- What is the fare amount by time zone
- What is the total amount by drop off month
- What is the total amount by pickup month 


### Data Analysis

Include some interesting formula worked with

```
 POWER BI
- No of Borough = DISTINCTCOUNT(taxi_zones[Borough])
- No of Zone = DISTINCTCOUNT(taxi_zones[Zone])

```

### Results/Findings

The analysis results are summarized as follow:
1.	Most of the payment for taxi was done by Credit Card 
2.	Boro Zone has over 50% of the fare amount by zone which make it the zone with highest fare amount 
3.	From 2017-2019 the total pickup amount was very high from February to May but have a sharp decline from June to August and have slight increase from September to December, same scenario for drop off amount 
4.	In 2020 the total pickup amount maintains a steady from April to December after a great decline from High amount from January to March, same scenario for drop off amount
5.	From 2017-2020 Central Harlem North maintain the most zone with highest amount 
6.	From 2017-2020 Manhattan has the most mount by Borough
 

### Recommendation

Based on the analysis, we recommend the following actions:
-	That payments for taxi should done mostly by Credit Card to promote cashless policy
-	Fare (Discount) amount should be more promoted at the zone with low fare zone amount, this will enable more patronage 
-	Other zones in New York should encourage the uses of taxi 


### References
Marie Jones (Lead Dispatcher, NYC Green Taxis)
