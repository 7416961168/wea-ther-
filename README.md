# 🌦 Weather Now

A simple React app to check current weather conditions for any city using the **Open-Meteo API**.


## 🚀 Features
- Search weather by city name
- Shows temperature, wind speed, and time
- Responsive design with Tailwind CSS
- Error handling for invalid city names or network issues


## 🛠 Tech Stack
- React
- Tailwind CSS
- Open-Meteo API (Geocoding + Weather)


## 🔗 APIs Used
1. Geocoding API:  
   `https://geocoding-api.open-meteo.com/v1/search?name={city}`  
2. Weather API:  
   `https://api.open-meteo.com/v1/forecast?latitude={lat}&longitude={lon}&current_weather=true`


## 📦 Installation
```bash
# Clone repo
git clone https://github.com/your-username/weather-now.git
cd weather-now

# Install dependencies
npm install

# Run the app
npm start
