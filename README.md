# WeatherApp
 A simple weather app built using HTML, CSS, and JavaScript.
 This weather app allows users to search for current weather conditions and hourly forecasts by city.

 
Features
- Search for weather by city
- Display current temperature, condition, and icon
- Display hourly forecast for the next 24 hours
- Error handling for invalid city names

  Code Structure
- index.html: Main HTML file
- style.css: CSS styles
- script.js: JavaScript code
- images/: Weather icon images

Functions
- getWeather(): Fetches current weather and hourly forecast data
- displayWeather(data): Displays current weather information
- displayHourlyForecast(hourlyData): Displays hourly forecast data
- showImage(): Displays weather icon

Variables
- apiKey: OpenWeatherMap API key
- city: User-input city name
- currentWeatherUrl: URL for current weather API request
- forecastUrl: URL for hourly forecast API request
