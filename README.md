  <h1 align="center"> Weather API Consumption and Database Persistence Project </h1>
  
![WEATHER](https://github.com/Lauuaguiar/Lauuaguiar/assets/145450311/d148d92b-20cf-4795-a381-27cf448cacf9)

<p align="left">
   <img src="https://img.shields.io/badge/STATUS-PROJECT%20COMPLETED-green">
   </p>

<h4 align="center">
:white_check_mark: Project completed :white_check_mark:
</h4>


## General Information
- **Subject:** Data Science Application Development
- **Course:** Data Science Engineering Degree
- **School:** School of Computer Engineering
- **University:** University of Las Palmas de Gran Canaria

## Functionality Summary
This project focuses on retrieving meteorological data from specific locations across the 8 Canary Islands. The data is sourced from the free REST API, OpenWeatherMap, providing weather forecasts every 3 hours for the upcoming 5 days. The application's aim is to collect and store this meteorological information (temperature, precipitation, wind speed, humidity, and cloud condition) into a database named DataBase.db. Data gets updated every 6 hours, storing information solely for 12:00 PM of each day.

## :open_file_folder: How to Run the Project?
To run the project, a 'locations.csv' file is required, containing latitude and longitude values for each desired point on the island. The file should follow this format: latitude1, longitude1, island1... Additionally, adding our API Key to the 'args[0]' variable is necessary. How can this be done? Check out the tutorial below:

[Tutorial Video](https://github.com/Lauuaguiar/Lauuaguiar/assets/145450311/898aeb83-8f7e-414b-8c7e-fa9cee9218fb)

The video demonstrates retrieving the ApiKey and accessing the class that utilizes it.

## Resources Used
- **Development Environment:** IntelliJ IDEA
- **Version Control Tools:** Git, GitHub
- **Documentation Tools:** Markdown, Stack Overflow, Reddit, ChatGPT, OpenWeatherMap, Youtube...

## Design
For this project's design, principles of modularity, maximum cohesion, and minimum coupling were followed. The MVC architecture style was employed to ease the code's structure. The project is built on a class architecture that relates as follows:

- *Class Diagram*: (Include an image of the class diagram and the dependency relationships).

## Submission
The project's repository is available on [GitHub](https://github.com/Lauuaguiar/Weather.git). The source code and documentation are located in the `src` and `docs` folders, respectively.
