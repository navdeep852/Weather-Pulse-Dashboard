# 🌦️ Weather Pulse Dashboard

An interactive Power BI dashboard to track **current weather**, **weekly forecasts**, and **air quality index (AQI)** across multiple cities. It is built using real-time weather data fetched from [WeatherAPI](https://www.weatherapi.com/) and designed with a modern dark theme for better visualization and user experience.

---

## 📊 Overview

The **Weather Pulse Dashboard** provides real-time insights into:
- Temperature, Humidity, Wind Speed, Visibility
- Precipitation, Air Pressure, UV Index
- Air Quality (PM2.5, PM10, O3, SO2, CO, NO2)
- Sunrise & Sunset Timings
- Rain Probabilities & Weekly Trends

---

## 🛠️ Tech Stack

- **Tool**: Microsoft Power BI  
- **Data Source**: [WeatherAPI.com](https://www.weatherapi.com/)  
- **Data Format**: JSON (converted to table using Power Query)  
- **Refresh**: Live or Daily depending on API limits  
- **Language**: DAX, M (Power Query), JSON  

---

## 🔌 API Integration

- Used Power Query’s Web connector to call WeatherAPI
- Endpoints: `current.json`, `forecast.json`, `airquality.json`
- Parameters: `city`, `days=7`, `aqi=yes`
- Fallback mechanism implemented for API failure

---

## 🧱 Dashboard Components

- **Cards**: Temperature, Humidity, Wind Speed, Visibility, UV Index
- **Line Chart**: 7-day temperature forecast
- **Bar Chart**: Rain probability
- **Donut Chart**: AQI category visualization
- **Slicer**: City selection (Chennai, Gurgaon, Lucknow, etc.)
- **Text Box**: Sunrise and Sunset
- **Gauge**: Real-time AQI index

---

## 🔍 Key Features

- ✅ Real-time city-wise weather insights  
- ✅ Weekly temperature & rain probability trends  
- ✅ AQI alerts for sensitive groups  
- ✅ Sunrise and Sunset timings for planning  
- ✅ Dark theme with modern UX  

---

## 🧩 Challenges Faced

- ⚠️ API call limitations → Solved using optimized refresh intervals
- ⚠️ Missing data → Addressed using rolling averages
- ⚠️ Visual clutter → Solved via card-based clean layout

---

## 🚀 Future Enhancements

- Add historical trend charts (Temperature & AQI)
- Radar-based cloud coverage visual
- Mobile-responsive Power BI layout
- Live city search and notification support

---

## 📌 Project Use Cases

- Portfolio showcase for data analysts  
- College or academic Power BI project  
- Real-time environmental monitoring  
- Demo for API integration in BI tools  

---

## 📁 File Info

- `Weather Pulse Dashboard Documentation.pdf`: Full documentation
- `.pbix` file (upload separately): Power BI Dashboard file

---

## 👤 Author

**Navdeep Maurya**  
Data Analyst | Weather & BI Enthusiast

📅 Project Date: July 2025  
📧 Contact: [LinkedIn](https://www.linkedin.com/in/navdeep-maurya/) *(replace with actual profile)*

---

## ⭐ Give a Star!

If you liked this project, feel free to ⭐ this repository and share it with others!
