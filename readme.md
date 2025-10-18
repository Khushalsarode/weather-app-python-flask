# 🌦 Weather App

<img src="https://cdn-icons-png.flaticon.com/512/1116/1116453.png" alt="weather_app_logo" width="100">

![Flask](https://img.shields.io/badge/Flask-2.0+-blue.svg)
![Python](https://img.shields.io/badge/Python-3.8+-green.svg)
![API](https://img.shields.io/badge/OpenWeatherMap-API-orange.svg)
![Bootstrap](https://img.shields.io/badge/Bootstrap-Frontend-purple.svg)
![License](https://img.shields.io/badge/License-MIT-yellow.svg)
![Status](https://img.shields.io/badge/Status-Active-success.svg)

---

## 🧭 Introduction

A responsive, feature-rich **Weather Dashboard** built using **Flask**, providing **real-time weather updates**, **5-day forecasts**, **air quality data**, and **interactive visualizations**.  
The app fetches weather information from the **OpenWeatherMap API** and enhances the user experience with **Chart.js** and **Leaflet.js** for visual interactivity.

This web app allows users to view the **current weather**, **forecast**, and **air pollution index** for any city in the world — or automatically detect and display weather for their **current location**.

---

## ✨ Features

- 🔍 Search weather by **city name** or **use current location**.
- 🌡️ View **temperature**, **feels like**, **humidity**, **pressure**, **wind**, and **visibility**.
- 🍃 Display **Air Quality Index (AQI)** with pollutants (PM2.5, PM10, O₃).
- 📊 **5-Day Forecast Chart** using Chart.js.
- 🗺️ Interactive **map view** with Leaflet.js.
- 🌈 **Dynamic background** changes based on weather conditions.
- 📱 Fully **responsive** for desktop, tablet, and mobile.
- 💾 Stores **recent search history** using browser local storage.
- 🔄 Switch between **Celsius (°C)** and **Fahrenheit (°F)**.

---

## 🧠 Tech Stack

| Layer | Technologies Used |
|-------|--------------------|
| **Frontend** | HTML5, CSS3, Bootstrap 5, JavaScript |
| **Backend** | Python (Flask Framework) |
| **APIs** | [OpenWeatherMap API](https://openweathermap.org/api) |
| **Visualization** | Chart.js (for temperature and humidity trends) |
| **Map** | Leaflet.js (for city location) |
| **Storage** | Local Storage (recent searches) |

---

## 🗂 Folder Structure

```

weather-app/
│
├── app.py                   # Flask application
├── templates/
│   └── dashboard.html        # Main HTML template
├── static/
│   ├── css/
│   │   └── style.css         # Custom styles
│   ├── js/
│   │   └── script.js         # Frontend logic
│   └── images/
│       └── favicon.png       # App icon
├── requirements.txt          # Python dependencies
├── README.md                 # Project overview
└── CONTRIBUTION.md           # Setup, installation & contribution guide

```

---

## ⚙️ How It Works

1. The user enters a **city name** or clicks **"Use My Location"**.
2. The app sends a request to the **OpenWeatherMap API** to fetch:
   - Current weather data  
   - 5-day / 3-hour forecast  
   - Air pollution data (AQI)
3. Data is processed by Flask and displayed dynamically using **Chart.js** and **Leaflet.js**.
4. Weather backgrounds update based on conditions like sunny, cloudy, or rainy.

---

## 🧩 Architecture Overview

```text
+--------------------------+
|   User Interface (UI)    |
| HTML, CSS, JS, Bootstrap |
+-----------+--------------+
            |
            ↓
+--------------------------+
|      Flask Backend       |
|  Routes, API Handling    |
+-----------+--------------+
            |
            ↓
+--------------------------+
|  OpenWeatherMap APIs     |
|  (Weather, Forecast, AQI)|
+-----------+--------------+
            |
            ↓
+--------------------------+
|  Visualization Layer     |
| Chart.js & Leaflet.js    |
+--------------------------+
````

---

## 🌍 Example Use Case

* Type **"Pune"** → Displays real-time temperature, humidity, wind, and air quality.
* Click **“Use My Location”** → Detects your city and shows live weather.
* Switch to **°F** to see temperature in Fahrenheit, similarly **°C**.
* View **5-day forecast trends** and **city map**.

---

## 🪄 Future Enhancements

* 🕒 Hourly forecast feature
* 🌙 Dark/Light mode toggle
* 📍 Compare multiple cities
* 🌦️ Severe weather alerts
* 🧾 Historical weather trends

---

## 🪪 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

## 🤝 Contributing

For setup, installation, and contribution guidelines, refer to:
📘 [CONTRIBUTION.md](CONTRIBUTION.md)

---

## 💖 Acknowledgements

* 🌤 [OpenWeatherMap](https://openweathermap.org/) — Weather and Air Quality API
* 📈 [Chart.js](https://www.chartjs.org/) — Forecast Visualization
* 🗺️ [Leaflet.js](https://leafletjs.com/) — Interactive Map
* 🎨 [Bootstrap](https://getbootstrap.com/) — Responsive Frontend Framework

---

> “Wherever you go, no matter what the weather, always bring your own sunshine.” ☀️

