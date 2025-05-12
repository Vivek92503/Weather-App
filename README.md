# 🌦️ Weather App 

A weather app showing current conditions and forecasts using OpenWeatherMap API with location detection and temperature unit toggle.

# Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup Instructions](#setup-instructions)
- [How to Use](#hpw-to-use)
- [Troubleshooting](#trobleshooting)
- [Screenshots](#screenshots)
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
### 1. Frontend   
- HTML5
- CSS3
- JavaScript

### 2. APIs & Services
- OpenWeatherMap API - Weather data
- Browser Geolocation API - User location detection

### 3. Libraries
- Font Awesome (v6) - Weather icons
- Google Fonts - Typography

# ⚙️ Setup Instructions

### 1. Get an API Key
1. Go to [OpenWeatherMap](https://openweathermap.org/)
2. Click "Sign Up" and create a free account
3. Verify your email address
4. Log in and go to the [API Keys page](https://home.openweathermap.org/api_keys)
5. Generate a new key (takes 10-15 minutes to activate)

### 2. Run the Project
#### Option A: Quick Start
1. Open `index.html` in your browser
2. When prompted, enter your API key
3. The app will remember your key for next time

#### Option B: Manual Setup
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

# 📸 Screenshots
![Screenshot (281)](https://github.com/user-attachments/assets/7ea2ed1a-7fd4-441f-8da5-8e7c7a0e350e)
![Screenshot (282)](https://github.com/user-attachments/assets/6b29e84d-ad49-41b8-92dd-35148e801001)
![Screenshot (283)](https://github.com/user-attachments/assets/fb764d1f-df90-41ab-9645-4dfe46033482)
![Screenshot (284)](https://github.com/user-attachments/assets/a3c5f490-a2eb-46f9-a75f-c0514f9f7726)
![Screenshot (286)](https://github.com/user-attachments/assets/f250be6d-390b-49f7-bda1-3672ec52bb26)

# 🧾 License

This project is licensed under the [MIT License](opensource.org/licenses/MIT).





