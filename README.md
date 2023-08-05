# Weather App

This is a simple weather app that allows users to retrieve weather information for a specific city. It uses the OpenWeatherMap API to fetch weather data and displays it in a user-friendly interface.


## Features

- Input field to enter the city name
- Search button to fetch weather data
- Displays temperature, weather condition, humidity, maximum, and minimum temperature
- Displays the city's unique ID

## Technologies Used

- HTML
- CSS (Styling)
- JavaScript (DOM Manipulation)
- OpenWeatherMap API for weather data

## How to Use

1. Clone this repository to your local machine.
2. Open the `index.html` file in a web browser.
3. Enter the name of the city you want to get weather information for.
4. Click the "Search" button.
5. The app will display weather information for the entered city.

## API Key

This app uses the OpenWeatherMap API to fetch weather data. You need to provide your own API key to make it work. Replace `'YOUR_API_KEY'` in the JavaScript code with your actual API key. You can sign up for an API key on the [OpenWeatherMap website](https://openweathermap.org/api).

```javascript
fetch(`https://api.openweathermap.org/data/2.5/weather?q=${city}&appid=YOUR_API_KEY`)
