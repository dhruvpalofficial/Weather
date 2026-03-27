# 🌤️ Wather - Weather App

**Flutter Version:** 3.11+ | **Dart Version:** 3.11+ | **License:** MIT

A beautiful and intuitive weather application built with Flutter that provides real-time weather information and forecasts for your current location.

## ✨ Features

- **Real-time Weather Data**: Get current temperature, weather conditions, wind speed, humidity, and pressure
- **Location-based**: Automatically detects your current location for accurate weather information
- **24-Hour Forecast**: View hourly weather predictions for the next 24 hours
- **Dark Theme**: Modern dark UI for comfortable viewing
- **Weather Icons**: Visual weather condition indicators
- **Metric Units**: Temperature and measurements in Celsius and appropriate units

## 🚀 Installation

### Prerequisites

- Flutter SDK (^3.11.0)
- Dart SDK (^3.11.0)
- Android Studio or VS Code with Flutter extensions

### Setup

1. **Clone the repository**

   ```bash
   git clone https://github.com/your-username/wather.git
   cd wather
   ```

2. **Install dependencies**

   ```bash
   flutter pub get
   ```

3. **Get OpenWeatherMap API Key**
   - Sign up at [OpenWeatherMap](https://openweathermap.org/api)
   - Get your free API key
   - Replace the `appkey` in `lib/my_app.dart` with your API key

4. **Run the app**
   ```bash
   flutter run
   ```

## 📱 Usage

1. **Grant Location Permission**: The app will request location access to provide weather for your current position
2. **View Current Weather**: See temperature, weather condition, and additional details
3. **Check Hourly Forecast**: Scroll through the 24-hour weather prediction
4. **Automatic Updates**: Weather data refreshes based on your location

## 🛠️ Dependencies

This project uses the following main dependencies:

- **geolocator**: For accessing device location services
- **http**: For making network requests to weather APIs
- **intl**: For date and time formatting

## 🏗️ Architecture

The app follows a clean architecture pattern with the following components:

- **Location Service** (`location.dart`): Handles GPS location retrieval
- **Network Service** (`network.dart`): Manages API calls to OpenWeatherMap
- **Weather Display** (`my_app.dart`): Main UI and state management
- **Additional Info** (`Additionalinfo.dart`): Displays detailed weather metrics
- **Hourly Forecast** (`scrollrow.dart`): Horizontal scrollable hourly weather view

## 🔧 API Integration

The app integrates with the OpenWeatherMap API to fetch weather data:

- **Current Weather**: 5-day/3-hour forecast endpoint
- **Data Points**: Temperature, humidity, pressure, wind speed, weather conditions
- **Units**: Metric system (Celsius, m/s, hPa)

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Weather data provided by [OpenWeatherMap](https://openweathermap.org/)
- Built with [Flutter](https://flutter.dev/)
- Icons from Material Design Icons

**Author:** Priyanshu Pal

---

**Note**: This is a personal project for learning Flutter development. Make sure to get your own API key from OpenWeatherMap for the app to function properly.
