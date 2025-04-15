# 🎮 Java Desktop Applications 💻

This repository contains two Java desktop applications:

1. **🐍 Snake Game** - A classic Snake game implementation using Java Swing
2. **☀️ Weather App** - A weather forecast application that fetches real-time weather data

## 🐍 Snake Game

### ✨ Overview
A classic Snake game where players control a snake to eat apples, growing longer with each apple consumed. The game ends if the snake collides with itself or the boundaries of the playing field.

### 🌟 Features
- 🎮 Responsive keyboard controls (arrow keys)
- 🏆 Dynamic score tracking
- 🌈 Colorful snake representation(random colour generator for every second)
- 🎮Can manage speed in which you want to play and rates that apple appear (Apples can be customized to colourful boxes as well)
- 🎯 Game over screen with final score

### 🕹️ How to Play
1. Use arrow keys to control the snake's direction
2. Eat the randomly appearing apples to grow the snake and increase your score
3. Avoid colliding with the walls or the snake's own body
4. Try to achieve the highest score possible

## ☀️ Weather App

### ✨ Overview
A desktop weather application that fetches real-time weather data from Open-Meteo API and displays it in a user-friendly interface.

### 🌟 Features
- 🔍 Search for weather by location name
- 🌡️ Display current temperature
- ☁️ Show weather conditions (Clear, Cloudy, Rain, Snow)
- 💧 Display humidity percentage
- 💨 Show current wind speed
- 🎨 Visual representations for different weather conditions

### 📱 How to Use
1. Enter a location name in the search field
2. Click the search button
3. View current weather data including:
   - 🌡️ Temperature in Celsius
   - ☁️ Weather condition with appropriate icon
   - 💧 Humidity percentage
   - 💨 Wind speed in km/h

## 🔧 Technical Details

### 🐍 Snake Game
- 🖼️ Built with Java Swing for the GUI
- ⏱️ Uses a timer-based game loop
- ⌨️ Implements keyboard listener for controls
- 📏 Grid-based collision detection

### ☀️ Weather App
- 📡 Fetches data from Open-Meteo API
- 📊 Uses JSON parsing for weather data processing
- 🗺️ Implements geolocation to convert city names to coordinates
- 🖼️ Built with Java Swing for the GUI interface

## 📋 Requirements
- ☕ Java JDK 19 or higher
- 🌐 For Weather App: Internet connection for API calls
- 📚 org.json.simple library (for Weather App)

## 📥 Installation

1. Clone this repository:
```
git clone https://github.com/chaitra-adiga/java_projects
```

2. Open the project in your preferred Java IDE (IntelliJ IDEA recommended as the project files are included)

3. For the Weather App, ensure you have the org.json.simple library in your classpath

## 🚀 Running the Applications

### 🐍 Snake Game
Run the `SnakeGame.java` file to start the Snake game.

### ☀️ Weather App
Run the `AppLauncher.java` file to start the Weather application.

## 💡 Future Improvements

### 🐍 Snake Game
- 🔄 Add difficulty levels
- 🏆 Implement high score tracking
- 🔊 Add sound effects
- 🎨 Create custom themes

### ☀️ Weather App
- 📅 Add multi-day forecast
- ❤️ Implement location favorites
- 🔄 Add temperature unit conversion (Celsius/Fahrenheit)
- 📊 Include more weather details (pressure, UV index, etc.)

## 📜 License
[MIT License](LICENSE)

## 👏 Acknowledgments
- ☁️ Weather data provided by [Open-Meteo API](https://open-meteo.com/)
- 🗺️ Geocoding services provided by [Open-Meteo Geocoding API](https://open-meteo.com/en/docs/geocoding-api)
