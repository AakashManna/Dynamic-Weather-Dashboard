-----

## Weather App

Welcome to the Weather App repository\! This project is a web application that provides real-time weather updates for any location. It utilizes **HTML**, **CSS**, and **JavaScript** to deliver a user-friendly interface and fetches data using the **OpenWeatherMap API**.

-----

## Features

  - **Live Weather Data**: Get up-to-date weather information for your current location or search for any city worldwide.
  - **5 Days Forecast**: See your city's weather forecast for the next 5 days.
  - **Explore Section**: View the weather for a selection of random cities in the Explore section.
  - **Add More Cities**: You have the ability to save and view the weather for additional cities.

### Technologies Used

  - **Frontend**: HTML, CSS, JAVASCRIPT
  - **API**: [OpenWeatherMap](https://openweathermap.org/)
  - **Icons**: [Fontawesome](https://fontawesome.com/)

### Additional Information on API Endpoints

  - **Geocoding API**: To get the name of the location (city or area name) by using longitude and latitude:
      - `https://openweathermap.org/api/geocoding-api`
  - **Current Weather Data**: To get the current weather for a location:
      - `https://openweathermap.org/current`
  - **5-Day Forecast**: To get the 5-day weather forecast:
      - `https://openweathermap.org/forecast5`

-----

## Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

  - A modern web browser.
  - An API key from [OpenWeatherMap Api](https://home.openweathermap.org/api_keys)

### Installation

1.  Clone the repository:
    ```sh
    git clone https://github.com/kaushalsahu07/weather.git
    ```
2.  Navigate to the project directory:
    ```sh
    cd weather
    ```
3.  Change the API key for all the JavaScript files, replacing `"Your API Key"` with your actual key:
    ```javascript
    let apiKey = "Your API Key";
    ```
4.  Open `index.html` in your browser to view the project.

### Usage

To use the Weather App, simply enter the name of the city in the search bar and press enter. The app will display the current weather conditions, including temperature, humidity, wind speed, and more.

-----
