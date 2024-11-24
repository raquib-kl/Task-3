# Task-3

# Weather Alert Mobile App System 🌤️

This repository contains a mobile application built with Flutter that fetches weather data from the OpenWeatherMap API and displays it in an easy-to-use interface. You can customize the app to include heat wave alerts and notifications for extreme weather conditions.

---

## Overview
Weather conditions play a significant role in our daily lives. This app provides users with real-time weather updates for any location. It can be extended to include alerts for extreme weather conditions like heat waves, ensuring user safety.

---

## Features
- Fetches real-time weather data from the **OpenWeatherMap API**.
- Displays weather details, including temperature, humidity, wind speed, and forecast.
- **Heat Wave Alerts**: (Customizable) Notify users of extreme heat conditions.
- Simple and responsive UI designed using **Flutter**.
- Cross-platform: Works on both Android and iOS devices.

---

## Requirements
To run this app, ensure you have the following:
- **Flutter SDK**: [Install Flutter](https://flutter.dev/docs/get-started/install)
- **Dart Programming Language** (Included with Flutter)
- **Android Studio or VS Code**: For development and running the app.
- An **API Key** from [OpenWeatherMap](https://openweathermap.org/api).

---

## Usage
- **View Current Weather**: Enter a city name or allow the app to detect your location to display weather data.
- **Heat Wave Alerts**: Customize the app to notify users if the temperature exceeds a predefined threshold.

---

## API Integration
This app uses the **OpenWeatherMap API** to fetch weather data. You can explore additional API features like hourly forecasts, air quality, and severe weather alerts. 

#### Key API Endpoints:
- **Current Weather**:  
  `https://api.openweathermap.org/data/2.5/weather?q={city_name}&appid={API_key}`
- **Forecast**:  
  `https://api.openweathermap.org/data/2.5/forecast?q={city_name}&appid={API_key}`

---

## Future Enhancements
- **Real-Time Alerts**: Integrate weather alert notifications for severe weather conditions (e.g., storms, extreme heat).
- **Geolocation Support**: Use device GPS to automatically fetch the user's location.
- **Offline Mode**: Cache the last retrieved weather data for offline use.
- **Wearable Integration**: Extend support for wearables like smartwatches.

---

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Feel free to contribute to this project or suggest improvements. Let’s make weather apps smarter and more useful! 🌟
