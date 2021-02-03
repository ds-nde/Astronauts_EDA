# Astronauts_EDA

Over 500 astronauts from almost 40 countries have traveled to space. Search the CSIS Aerospace Security International Astronaut Database below for an individual astronaut’s name, country of origin, gender, and flight records. Sort by category by clicking the column headers.

The definition of “astronaut” is not unanimously agreed upon among the world’s space launch providers. This database includes all those who have flown to an altitude of 100 kilometers or higher. This particular definition of “outer space” is used by the World Air Sports Federation (FAI), an international record-keeping body for aeronautics and astronautics. This database also includes those who were killed in a space-bound mission, like the first-time astronauts aboard STS-51-L. It does not include, however, those who have flown to altitudes below 100 kilometers or first-time astronauts who were killed in non-space-bound missions without having previously flown to space.

Some astronauts flew to space and returned to Earth on two different spacecraft. In those cases, only the ascent vehicle is included in the “Flights” column.

The interactive data visualization at the top of this page shows the total number of human passengers sent to space per year, not the number of unique astronauts. That is, if one astronaut were flown two times in 2020, the chart would describe two flights, not one.


## Data on astronauts
* astronauts.csv
* id - row ID
* number - Astronaut ID
* name 
* original_name - Name in original language
* sex 
* year_of_birth 
* nationality - Astronaut's nationality
* military_civilian - Military status
* selection - Name of selection program
* year_of_selection - Year of selection program
* mission_number 
* total_number_of_missions 
* occupation
* year_of_mission
* mission_title
* ascend_shuttle - Name of the shuttle used for ascend
* in_orbit - Name of spacecraft used in orbit
* descend_shuttle - Name of the shuttle used for descend
* hours_mission - Duration of the mission in hours
* total_hrs_sum - Total duration of all missions in hours
* eva - Number of instances of extravehicular activities by mission
* eva_hrs_mission - Duration of all extravehicular activities during the mission in hours
* total_eva_hrs - Total duration of all extravehicular activities in hours

## Data on missions
missions.csv
ID
Company name
Location - Location of launch
Date - Date and time of launch
Detail - Full rocket name
Status Rocket - Status of the rocket
Cost - Cost of the mission in million $
Status Mission - Status of the mission
