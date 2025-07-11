# Real-Time-Weather-AQI-Dashboard-using-Power-BI-WeatherAPI

This project is a dynamic **Power BI dashboard** that integrates real-time weather data, 7-day forecasts, and live air quality information using the **WeatherAPI**.

📍 Cities Covered:
- Raipur
- Bengaluru
- Hyderabad
- Noida
- Lucknow

---

## ✅ Features Included

### 📅 7-Day Weather Forecast
- Daily high temperatures
- Weather conditions (e.g., sunny, mist, rain)

### 🌧️ Daily Chance of Rain
- Rain probability (%) for each of the next 7 days

### 🌡 Live Real-Time Weather
- Temperature, Humidity, Wind Speed, Visibility
- Pressure, UV Index, Sunrise/Sunset

### ☣️ Air Quality Index (AQI)
- PM2.5, PM10, SO2, NO2, CO, O3
- Color-coded AQI levels
- Health suggestions & status based on AQI

---

## 📸 Dashboard Preview

![Dashboard Screenshot](./Screenshot%202025-07-11%20182605.png)

---

## 🛠️ How It Works

### 🔑 Step 1: Get Your API Key
Sign up at [WeatherAPI.com](https://www.weatherapi.com/) and get your free API key.

---### 🌐 Step 2: API URLs Used

#### Current Weather:
https://api.weatherapi.com/v1/current.json?key=YOUR_API_KEY&q=CITY_NAME

#### 7-Day Forecast:
https://api.weatherapi.com/v1/forecast.json?key=YOUR_API_KEY&q=CITY_NAME&days=7

yaml
Copy
Edit

---

### 🧠 Step 3: Load into Power BI

1. Get Data → Web → Paste API URLs
2. Expand JSON fields: `current`, `condition`, `air_quality`, `forecast`
3. Add a custom column for city name
4. Clean and load into the model

---

### 🎨 Step 4: Design Dashboard

- Cards for Temperature, Humidity, UV, etc.
- Line charts for forecast
- Rain probability bar chart
- AQI tiles with icons, colors, and DAX-based suggestions


---

📥 Download the Report (.pbix)
➡️ Click here to download WeatherDashboard.pbix
