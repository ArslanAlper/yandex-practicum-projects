## Project description

In this project, I have worked as an analyst for a new ride-sharing company in Chicago. My task was to find the patterns in the available information, to try to understand passenger preferences and the impact of external factors on rides.

I have worked with a database, analyzed data from competitors and tested hypotheses about the impact of weather on ride frequency. 

From the previous sections, I had retrieved the data using SQL, then created two different datasets from them. In the following steps, we will complete the other steps using Python.

## Description of the data

A database with info on taxi rides in Chicago:
- **neighborhoods table:** data on city neighborhoods
- **name:** name of the neighborhood
- **neighborhood_id:** neighborhood code
- **cabs table:** data on taxis
- **cab_id:** vehicle code
- **vehicle_id:** the vehicle's technical ID
- **company_name:** the company that owns the vehicle
- **trips table:** data on rides
- **trip_id:** ride code
- **cab_id:** code of the vehicle operating the ride
- **start_ts:** date and time of the beginning of the ride (time rounded to the hour)
- **end_ts:** date and time of the end of the ride (time rounded to the hour)
- **duration_seconds:** ride duration in seconds
- **distance_miles:** ride distance in miles
- **pickup_location_id:** pickup neighborhood code
- **dropoff_location_id:** dropoff neighborhood code

## Table scheme

![table scheme](https://user-images.githubusercontent.com/61430166/215336622-00a7c981-1775-45ab-b46d-5820c9d441a2.png)

