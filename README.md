# SkyForecastor - Weather App

## Overview

**SkyForecastor** is a simple, responsive web application that allows users to check real-time weather information for any city worldwide. By entering a city name, users can view weather details such as temperature, humidity, weather description, and an emoji that represents the current weather conditions. This project was built using **HTML**, **CSS**, and **JavaScript** and pulls data from the **OpenWeatherMap API**.

---

## Features

- **Search for Any City**: Enter a city name and receive live weather data.
- **Weather Information Display**: View temperature (in Celsius), humidity, and a description of the weather conditions.
- **Weather Emojis**: Display weather-specific emojis based on the weather conditions (e.g., 🌧️ for rain, ❄️ for snow).
- **Responsive Design**: The app adapts seamlessly to different screen sizes, making it user-friendly on both desktop and mobile devices.

---

## Technologies Used

- **HTML**: Structure of the weather app.
- **CSS**: Styling and layout for a clean and intuitive UI.
- **JavaScript**: Dynamic behavior, including fetching weather data and updating the interface.
- **OpenWeatherMap API**: Provides the real-time weather data.
- **Flexbox**: For responsive design, ensuring the layout works well across devices.

---

## How It Works

1. **City Input**: The user types the name of a city into the input field.
2. **API Request**: Upon submitting the form, the app makes a request to the **OpenWeatherMap API** to fetch the weather data for the specified city.
3. **Weather Display**: The app processes the returned data and displays:
   - The city name.
   - Current temperature in **Celsius**.
   - Humidity percentage.
   - Weather description (e.g., clear, cloudy, rainy).
   - A weather emoji based on the weather conditions.
4. **Error Handling**: If the city is not found or there’s an error in fetching the data, an appropriate error message will be displayed to the user.

---

