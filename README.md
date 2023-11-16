  <h1 align="center"> WEATHER APP </h1>
  
![WEATHER](https://github.com/Lauuaguiar/Lauuaguiar/assets/145450311/d148d92b-20cf-4795-a381-27cf448cacf9)

<p align="left">
   <img src="https://img.shields.io/badge/STATUS-PROJECT%20COMPLETED-green">
   </p>

<h4 align="center">
:white_check_mark: Project completed :white_check_mark:
</h4>

## :hammer:Functionality of the project
This app is designed to gather meteorological data from specific points across the 8 Canary Islands. The data is provided by the free REST API Open Weather Map, which gives us weather data every 3 hours for the next 5 days. The goal of this application is to retrieve this meteorological information (temperature, precipitation, wind speed, humidity, and cloud condition) and store it in a database, named DataBase.db in our case. This data gets updated every 6 hours, and for each day, it only saves the weather data at 12:00 PM

## :open_file_folder: How to run the project?
In order to run the project, a .csv file named 'locations.csv' is required. This file should contain the latitude and longitude of each point on the island from which we want to obtain data. The file should follow this format: latitude1, longitude1, island1... Additionally, we will need to add our own ApiKey to the 'args[0]' variable. How can this be done? Below is a tutorial:

https://github.com/Lauuaguiar/Lauuaguiar/assets/145450311/898aeb83-8f7e-414b-8c7e-fa9cee9218fb

In the video, we see the ApiKey and the path to the class that uses it.
