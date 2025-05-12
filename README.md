# 🎯 Weather App 🌦️

A weather app showing current conditions and forecasts using OpenWeatherMap API with location detection and temperature unit toggle.

# Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup Instructions](#setup-instructions)
- [Deployment](#deployment)
- [Notes](#notes)
- [License](#license)

# 📌 Introduction 
This weather application provides real-time weather data and 5-day forecasts for any location worldwide. Users can search by city or use GPS for automatic location detection. The app displays temperature (with °C/°F toggle), humidity, wind speed, and weather conditions with visual icons. Built with HTML, CSS, and JavaScript, it uses the OpenWeatherMap API and features a clean, responsive design suitable for all devices. Perfect for quick weather checks.

# 🚀 Features
- Current weather conditions
- 5-day forecast
- Location-based weather
- Temperature unit toggle (°C/°F)
- Weather icons
- Responsive design

# 🛠️ Technologies Used
## Frontend:  
  ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
  ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
  ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

**APIs & Services**
- OpenWeatherMap API - Weather data
- Browser Geolocation API - User location detection

## Libraries
- Font Awesome (v6) - Weather icons
- Google Fonts - Typography

# ⚙️ Setup Instructions

## 1. Get an API Key
1. Go to [OpenWeatherMap](https://openweathermap.org/)
2. Click "Sign Up" and create a free account
3. Verify your email address
4. Log in and go to the [API Keys page](https://home.openweathermap.org/api_keys)
5. Generate a new key (takes 10-15 minutes to activate)

## 2. Run the Project

### Option A: Quick Start
1. Open `index.html` in your browser
2. When prompted, enter your API key
3. The app will remember your key for next time

### Option B: Manual Setup
1. Create a file named `config.js` in the project folder
2. Add this line to it:
   ```javascript
   const API_KEY = 'YOUR_API_KEY_HERE';

# How to Use
- Enter a city name and click "Get Weather"
- Or click "Current Location" to use your GPS
- Toggle between °C/°F using the switch button

# Troubleshooting
**❌ "Invalid API Key" error**
- Wait 10-15 minutes after generating your key
- Make sure you copied the entire key
- Check for extra spaces in the key

**❌ Location not working**
- Make sure you've allowed browser location permissions
- Try searching by city name instead

# 🧾 License

This project is licensed under the [MIT License](opensource.org/licenses/MIT).





