# Aviation-Data-Analysis-Excel
Navigating the Complexities of Airline and Airport Operations.
![image](https://github.com/user-attachments/assets/b763c7c0-b08b-49e1-8b6f-e8a48abc159d)



# Project Link
https://1drv.ms/x/c/30b827ffad58e85a/ET-zdlmWD5lJhjOFA2qTK4IBRqe7pwpeLNcysdojMZId4w?e=cCYDzT

# Sky Analytics: Navigating the Complexities of Airline and Airport Operations Using Excel

## Background

* SkyNet Analysis Inc. is a leading consultancy firm specializing in aviation analytics. With the aviation industry's rapid expansion and the increasing complexity of global air travel, SkyNet plays a critical role in providing data-driven insights to airlines, airports, and regulatory bodies.
* The company has access to extensive datasets that cover a wide range of information, including flight schedules, delays, airline operations, and airport traffic details.
* These datasets offer a unique opportunity to explore and understand the multifaceted nature of the aviation industry, from operational efficiency and customer satisfaction to logistical challenges and environmental impact.

## Objective

* The primary objective of this case study, titled "Sky Analytics: Navigating the Complexities of Airline and Airport Operations," is to deeply analyze and interpret the extensive datasets encompassing flights, airlines, and airports - namely "flights.csv", "airlines.csv", and "airports.csv".
* The analysis aims to uncover critical insights into flight operations, delay patterns, airline efficiency, and airport traffic dynamics.
* By exploring these datasets, the study seeks to identify key factors influencing operational efficiency, understand the intricacies of flight scheduling and delays, and evaluate the performance metrics of airlines and airports.
* The ultimate goal is to provide strategic recommendations to enhance operational effectiveness, improve customer experiences in air travel, and contribute to the overall advancement of the aviation industry's standards and practices.

## Data Sources

### Flights Dataset (`flights.csv`)
* `YEAR`
* `MONTH`
* `DAY`
* `DAY_OF_WEEK`
* `AIRLINE`
* `FLIGHT_NUMBER`
* `TAIL_NUMBER`
* `ORIGIN_AIRPORT`
* `DESTINATION_AIRPORT`
* `SCHEDULED_DEPARTURE`
* `DEPARTURE_TIME`
* `DEPARTURE_DELAY`
* `TAXI_OUT`
* `WHEELS_OFF`
* `WHEELS_ON`
* `SCHEDULED_TIME`
* `ELAPSED_TIME`
* `AIR_TIME`
* `DISTANCE`
* `TAXI_IN`
* `SCHEDULED_ARRIVAL`
* `ARRIVAL_TIME`
* `ARRIVAL_DELAY`
* `DIVERTED`
* `CANCELLED`
* `CANCELLATION_REASON`
* `AIR_SYSTEM_DELAY`
* `SECURITY_DELAY`
* `AIRLINE_DELAY`
* `LATE_AIRCRAFT_DELAY`
* `WEATHER_DELAY`
### Airlines Dataset (`airlines.csv`)

This dataset provides information about various airlines, with columns: IATA\_CODE and AIRLINE.

### Airports Dataset (`airports.csv`)

This dataset contains information about various airports, with columns: IATA\_CODE, AIRPORT, CITY, STATE, COUNTRY, LATITUDE, LONGITUDE.

## Key Findings/Insights

This analysis of the aviation datasets revealed several key insights into flight operations, airline performance, and airport activity:

* **Missing Data:** Identified patterns in missing data, particularly related to cancelled flights.
* **Flight Delays:** American Airlines Inc. had the highest average airline delay.
* **Airport Traffic:** ATL (Atlanta) was identified as the busiest airport based on total traffic (incoming and outgoing flights).
* **Flight Cancellations:** American Eagle Airlines Inc. had the highest cancellation rate, with a significant portion of cancellations due to reason 'B'.
* **Seasonal Variations:** Limited to two months of data, making it difficult to determine reliable seasonal trends.
* **Distance vs. Delays:** No strong positive correlation found between flight distance and arrival delay; shorter to medium-haul flights tended to have more delays.
* **Airline Efficiency (On-Time Performance):** Frontier Airlines Inc. showed the highest on-time performance.
* **Impact of Day of Week:** Mondays experienced the most operational disruptions (highest delays and cancellations), while weekends (especially Saturday) were smoother.
* **Airport Connectivity:** ATL (Atlanta) served the most unique destinations.
* **Flight Duration Accuracy:** Hawaiian Airlines Inc. had the least deviation between scheduled and actual flight times, while JetBlue Airways had the most.
* **Airline Fleet Utilization:** Southwest Airlines Co. showed the highest estimated fleet utilization (flights per aircraft).
* **Airport Geographical Analysis:** High concentration of airports observed in the central part of the contiguous US.
* **Delay Types:** Late Aircraft Delay and Airline Delay were the primary drivers of flight delays.
* **Long-Haul vs. Short-Haul:** Short-haul flights generally experienced slightly higher average arrival delays and cancellation rates for some airlines.
* **Airport Connectivity and Delays (Top 3):** ATL had the highest connectivity and relatively good on-time performance. ORD had high connectivity but the worst delay performance. DFW showed moderate delay levels.
* **Cumulative Delay Impact:** Southwest, Delta, and Atlantic Southeast faced the heaviest cumulative delay burden due to high flight volumes.
* **Primary Delay Cause by Time of Day:**
    * **Morning:** Lowest delays overall.
    * **Afternoon:** Increase in airline and system delays.
    * **Evening:** Late aircraft delays dominant.
    * **Night:** High delays due to late aircraft and airline-related issues.

## Excel Dashboard Overview

The interactive Excel dashboard provides a visual and analytical representation of key aspects of the aviation datasets. Key components include:

* **Flight Operations Overview:** Summary metrics for total flights, average delays, and cancellations with airline and airport filters.
* **Airline Performance Analysis:** Visualizations of average delay time, cancellation rates, and flight frequency per airline.
* **Airport Traffic Visualization:** Data on the busiest airports, including a pie chart for traffic distribution.
* **Delay Cause Breakdown:** Analysis of delay reasons (weather, security, airline, etc.) using stacked bar charts.
* **Time-based Flight Trends:** Charts showing how flight patterns and delay trends vary across different times of the day.
* **Interactive Filters:** Slicers and dropdown menus for users to explore data by time, airline, and airport.

## Conclusion

This analysis of airline and airport operations provides valuable insights into the complexities of the aviation industry. By examining flight patterns, delays, airline performance, and airport traffic, this study offers data-driven findings that can contribute to enhancing operational effectiveness and improving the overall air travel experience. The Excel dashboard further allows for interactive exploration of these key metrics, making the insights more accessible.
