# WeatherFast - Module 06 Challenge

## Mock Up

![This is a screenshot of my weather app](./assets/WeatherFast%20-%20Weather%20App.gif)

This is my completed code for the Module 06 challenge this week. We were given a task to use the OpenWeather One Call API to create our own weather app and utilize localStorage as well to store previous city searches.

## User Story

```
AS A traveler
I WANT to see the weather outlook for multiple cities
SO THAT I can plan a trip accordingly
```

The Acceptance Criteria is as follows:

## Acceptance Criteria

```
GIVEN a weather dashboard with form inputs
WHEN I search for a city
THEN I am presented with current and future conditions for that city and that city is added to the search history
WHEN I view current weather conditions for that city
THEN I am presented with the city name, the date, an icon representation of weather conditions, the temperature, the humidity, the wind speed, and the UV index
WHEN I view the UV index
THEN I am presented with a color that indicates whether the conditions are favorable, moderate, or severe
WHEN I view future weather conditions for that city
THEN I am presented with a 5-day forecast that displays the date, an icon representation of weather conditions, the temperature, the wind speed, and the humidity
WHEN I click on a city in the search history
THEN I am again presented with current and future conditions for that city
```

What I did to complete this challenge is take each individual criteria one at a time, while also trying to minimize repetativeness in the code. I started with making a basic layout using bootstrap to place all the correct cards in place. I then went on to link jquery and moment scripts before starting on my JS file. 

On the JS file, I started with adding variables for my search button and my API key from OpenWeather. I then added a for look to be able to add the cities that were previously searched into local storage. I then started to write teh if statements to pull the information from OpenWeather and to append the information I want to the HTML file. I then created the call for the 5 day forecast to show them as cards in the 5 day forecast section at the bottom of the page. The very last thing I did was add a bit of style via CSS to change a few colors and font sizes.

## Please see attached links to Repository and Deployed Page:
### https://github.com/jdanleano/weather-fast
### https://jdanleano.github.io/weather-fast
