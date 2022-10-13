# Exploratory Data Analysis on Airline On-Time Performance Data
## by Ismaheel Bello


## Dataset

> The data used for this analysis was downloaded from <a href='https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/HG7NV7'>ASA Statistical Computing Dataverse.</a>, the data downloaded is from 1987 - 2008, the data was then converted into .feather format and then read into a database for analysis.
The flight details consist of more than 180million rows, the plane_data has 5029 rows while the carrier data has 1491 rows. 
Some of the features used in the flight datasets are:
<ul>
<li> DepDelay: Departure delay of flight, this is the difference between the Actual departure time and Scheduled Departure time in minute. </li>
<li>ArrDelay : Arrival delay of flight, difference between Scheduled arrival time and the Actual Arrival time in minute. </li>
<li>NASDelay : Delay caused by NAS, measured in minutes. </li>
<li>SecurityDelay: Delay caused by Security, measured in minutes.</li>
<li>Year: Year of flight. </li>
<li>DAYOFWEEK : Day of Flight, month ranges from 1-7 ,in which 1 is Sunday... </li>
<li>Month: Month of Flight: Month ranges between 1 - 12, where 1 means January. </li>
<li>Diverted : Diverted Flights, 0 means No, 1 means Yes. </li>
<li>Cancellation : Cancelled flight,0 means No, 1 means Yes.</li>
<li>CancellationCode: Reasons for Cancellation, A = 'Carrier', B = 'Weather',C = 'NAS',D = 'Security'</li>
<li>LateAircraftDelay: Delay caused by LateAircraft in minutes.</li>
</ul>

>The engine_type feature was also used in the plane_data.

## Summary of Findings

> People travels on Sunday than in other days of the week, atleast in a day there are always more than 14000 flight. People tend to travel more during the month of March and then January than any other month of the year and people travel less in September and then February,In 2008, people travelled more than in any other year since 1987.
> Only on rare circumstance will a flight be cancelled, more than 98% of flight are not always cancelled. If flight is being cancelled. Approximately 43.78% of cancelled flight is caused by Carrier, 35.95% is due to Weather condition, 20.18% is caused by NAS, while 0.09% is due to security reason.
> Out of every 100 flights, 1 or no flight will be diverted. Also, if there is a delay in departure time, there will also be a delay in arrival time of flight. Late Arrival of Flight also has effect on the departure time and the arrival time of the flight.

> Also looking at the relationship between the engine_types and distance, we see that the turbo-shaft engine is most appropriate for travelling for both short and long distance.

## Key Insights for Presentation

> To know the most time people travel by flight.
> To know the factor which has more effect on the Arrival time of flights.

> 