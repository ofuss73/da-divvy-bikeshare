## Data Analysis of Divvy Bike Share in Chicago ##

As part of my Data Analytics course at [neuefische](https://www.neuefische.de), my capstone project with two other students was a Data Analysis of Divvy Bike Share trips in Chicago over the last 10 years. We worked on that project from 18th September 2023 until 16th October 2023. The final presentation of the project took place on 17th October 2023. The excerpt of the project, which you can see in this Github repository, is my personal share of the whole Capstone project.

Divvy offers anonymized data of all trips of their customers since the beginning in 2013. The data can be downloaded from [here](https://divvy-tripdata.s3.amazonaws.com/index.html). In addition to that, I bought weather data from [Openweather](https://openweathermap.org/history-bulk) for the period from June 2013 to August 2023.

The code for the Data Analysis in this repository is modified to use csv-files instead of an SQL-database during the capstone phase, because I don't have permanent access to the SQL-database anymore. I also added more code to check whether there are more zip-files with new trip-data available on the Divvy server.

In addition to that and if you want to continue the data analysis in future, you'll need newer weather data.
1. via Meteostat library in Python
2. via Openweather API 3.0 calls (you need a API key for it)
