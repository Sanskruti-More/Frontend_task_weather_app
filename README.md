**1.Overview**

The Weather App is a simple web application built with React that allows users to fetch and display current weather conditions for a specified city using the OpenWeather API.

**2.Features**

•	Search for weather details of any city.

•	Displays temperature, weather conditions, pressure, humidity, and wind speed.

•	Dynamic background changes based on temperature range.

•	Fetches real-time weather data from OpenWeather API.


  
**3.Technologies Used**

•	React: JavaScript library for building user interfaces.

•	CSS: Styling for the application.

•	OpenWeather API: Provides real-time weather data.



**4.API Details**

•	The application uses the OpenWeather API to fetch weather data.



**5.How to Run the Project**

1. Navigate to the project directory:
   
   cd weather-app
2.	Install dependencies:
   
    npm install
3.	Start the application:

    npm start
5.	Open your browser and go to http://localhost:3000/ to use the app.


**6.Dynamic Background**

The app changes its background based on the temperature:

•	≤ 15°C: Cold background (app cold)

•	16°C - 25°C: Light Cold background (app lcold)

•	26°C - 35°C: Moderate temperature background (app medium)

•	> 35°C: Warm background (app warm)





