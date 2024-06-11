# WeatherApp

Welcome to WeatherApp, your reliable and user-friendly weather application. Stay updated with real-time weather conditions, forecasts, and severe weather alerts for your location and any place around the world.

## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [API Reference](#api-reference)
- [Contributing](#contributing)
- [License](#license)

## Features
- **Real-time Weather Data:** Get the latest weather information including temperature, humidity, wind speed, and more.
- **5-Day Forecast:** Plan ahead with detailed weather forecasts for the next five days.
- **Severe Weather Alerts:** Receive notifications for severe weather conditions like storms, hurricanes, and extreme temperatures.
- **Location-based Services:** Automatically fetch weather data based on your current location.
- **Search Functionality:** Search for weather information by city, country, or coordinates.
- **User-friendly Interface:** Easy-to-use interface with clean and intuitive design.

## Installation
To install WeatherApp, follow these steps:

### Prerequisites
- Flutter installed on your system. You can download Flutter from the official [Flutter website](https://flutter.dev/docs/get-started/install).
- API key from a weather service provider (e.g., OpenWeatherMap, WeatherAPI).

### Steps
1. Clone the repository:
    ```sh
    git clone https://github.com/EzraAriwomoi/weatherapp.git
    cd weatherapp
    ```

2. Install dependencies:
    ```sh
    flutter pub get
    ```

3. Create a `.env` file in the root directory and add your API key:
    ```env
    WEATHER_API_KEY=your_api_key_here
    ```

4. Run the application:
    ```sh
    flutter run
    ```

## Usage
Once the application is running, you can use it to:
- View current weather conditions.
- Check the 5-day weather forecast.
- Receive alerts for severe weather conditions.
- Search for weather information in different locations.

### Interface Overview
- **Home Screen:** Displays current weather and basic forecast for your location.
- **Search Function:** Allows you to search for weather data by entering a city name or coordinates.
- **Alerts Section:** Shows any active weather alerts for your area.

## Configuration
You can customize WeatherApp by modifying the following configurations:

- **API Key:** Set your weather service API key in the `.env` file.
- **Default Location:** Change the default location by editing the configuration in `lib/config.dart`.

## API Reference
WeatherApp uses external APIs to fetch weather data. Below are some of the key endpoints:

### Current Weather Data
```
GET /weather?q={city name}&appid={API key}
```

### 5-Day Weather Forecast
```
GET /forecast?q={city name}&appid={API key}
```

### Severe Weather Alerts
```
GET /alerts?q={city name}&appid={API key}
```

Refer to the documentation of your chosen weather API provider for more details on available endpoints and parameters.

## Contributing
We welcome contributions to WeatherApp! To contribute, follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.

Please ensure your code adheres to our coding standards and includes appropriate tests.

## License
WeatherApp is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

Thank you for using WeatherApp! We hope it helps you stay prepared and informed about the weather.