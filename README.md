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

## 🛠️ How It Works

### 🔑 Step 1: Get Your API Key
Sign up at [WeatherAPI.com](https://www.weatherapi.com/) and get your free API key.

---

### 🌐 Step 2: API URLs Used

#### Current Weather:
https://api.weatherapi.com/v1/current.json?key=YOUR_API_KEY&q=CITY_NAME

#### 7-Day Forecast:
https://api.weatherapi.com/v1/forecast.json?key=YOUR_API_KEY&q=CITY_NAME&days=7

---

### 🧠 Step 3: Load into Power BI

1. Go to **Home → Get Data → Web**
2. Load both current and forecast endpoints
3. Expand nested JSON:
   - `current`, `condition`, `air_quality`
   - `forecast.forecastday` (for temperature & rain)
4. Add a `City` column
5. Clean and rename columns
6. Click **Close & Apply**

---

## 🎨 Visualizations

- 💳 Cards: Temperature, Humidity, UV, Pressure, Wind Speed
- 📈 Line Chart: 7-Day Forecasted Temperatures
- 📊 Bar Chart: Daily Rain Probabilities
- 🕗 Sunrise & Sunset times
- 🧭 Map View: Plot of Cities
- ☣️ AQI Panel: DAX-driven visuals (Color, Status, Suggestion)

---
