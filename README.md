Copyright © 2024 Mohammed. All rights reserved.

Unauthorized copying, redistribution, forking, or cloning of the content from this repository and other associated materials is strictly prohibited and will not be tolerated.

# Weather App

## Introduction
Welcome to Mohammed's Weather App! This simple and elegant weather application provides real-time weather information for your desired city. The user-friendly interface offers essential weather details, making it convenient for you to stay informed.

## Features
- **Search Functionality**: Enter the name of the city you want to check the weather for.
- **Weather Details**: Get accurate information about the temperature, humidity, and wind speed.
- **Visual Representation**: The app includes weather icons to visually represent the current weather conditions.
- **Responsive Design**: The app is designed to be responsive, ensuring a seamless experience across different devices.

## Usage
1. Enter the name of the city in the search bar.
2. Click the search button or press Enter to fetch the weather details.
3. Instantly view the current temperature, humidity, and wind speed for the specified city.

## Getting Started
To use Mohammed's Weather App, simply open the `index.html` file in your web browser. Ensure you have a working internet connection to fetch the latest weather data.

## Technologies Used
- HTML
- CSS
- JavaScript

## API Integration
The app utilizes the OpenWeatherMap API to retrieve accurate and up-to-date weather information.

```javascript
const apiKey = "[insert your personal key]";
const apiUrl = "https://api.openweathermap.org/data/2.5/weather?&units=metric&q=";

// Sample API Request
fetch(apiUrl + 'New York' + '$appid=${apiKey}')
    .then(response => response.json())
    .then(data => console.log(data));
