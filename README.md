# 🌦️ Live Weather Forecast Dashboard | Power BI

## 📖 About the Project

This project is an interactive weather analytics dashboard built in **Microsoft Power BI** by integrating live weather data from **WeatherAPI.com**. The goal was to create a dynamic dashboard that allows users to view real-time weather conditions and a three-day forecast for multiple cities through a clean and interactive interface.

Instead of using static datasets, the dashboard fetches weather information from the WeatherAPI service in **JSON format**. The JSON data is transformed using **Power Query**, modeled within Power BI, and enhanced with **DAX measures** to provide meaningful insights and a responsive user experience.

The dashboard updates automatically based on the selected city, making it easy to compare weather conditions across locations.

---

## 🚀 Key Features

- 🌍 Weather information for six Indian cities
- 📍 Interactive city selection
- 🌡️ Current temperature
- 📅 Current date and latest weather update
- 💧 Humidity
- 🌬️ Wind speed
- ☁️ Weather condition with icons
- 🌅 Sunrise & Sunset timings
- 🌧️ Chance of rain
- 🌫️ Air Quality (PM10)
- 📊 Three-day weather forecast
- 🎨 Dynamic AQI color indicators using DAX
- ⚡ Interactive Power BI visuals and slicers

---

## 🏙️ Cities Covered

- Bangalore
- Gurgaon
- Mumbai
- Lucknow
- Hyderabad
- Noida

---

## 🌐 Data Source

All weather information is retrieved from the **WeatherAPI** service.

**Website:** https://www.weatherapi.com/

The dashboard consumes weather data in **JSON format** using the Forecast API endpoint.

Example API:

```
https://api.weatherapi.com/v1/forecast.json
```

---

## 🛠️ Tech Stack

- Microsoft Power BI
- Power Query (M Language)
- DAX (Data Analysis Expressions)
- WeatherAPI
- JSON
- Data Modeling

---

## 📊 Dashboard Overview

The dashboard consists of multiple sections designed to provide a complete weather overview.

### Current Weather

Displays the latest weather details for the selected city, including:

- Current Temperature
- Weather Condition
- Feels Like Temperature
- Humidity
- Wind Speed
- Air Quality (PM10)
- Last Updated Time

### Three-Day Forecast

Provides weather predictions for the next three days, including:

- Maximum Temperature
- Minimum Temperature
- Average Temperature
- Chance of Rain
- Weather Condition
- Forecast Icons

### Air Quality

Shows PM10 air quality values with dynamic color coding for better visualization.

### Dynamic Date

Automatically displays the current weather date based on the selected city's latest API response.

---

## 🔄 Project Workflow

```
WeatherAPI
      │
      ▼
 JSON Response
      │
      ▼
 Power Query
(Data Cleaning & Transformation)
      │
      ▼
 Data Model
      │
      ▼
 DAX Measures
      │
      ▼
 Interactive Power BI Dashboard
```

---

## 🔧 Data Preparation

The raw JSON response was transformed using Power Query by:

- Parsing nested JSON records
- Extracting current weather information
- Expanding forecast data
- Extracting air quality metrics
- Changing data types
- Removing unnecessary fields
- Creating calculated columns for reporting

---

## 📈 DAX Measures Used

Some of the custom measures created in this project include:

- Current Date
- PM10 Status
- AQI Color Indicator
- Temperature Formatting
- Forecast Labels

---

## 📷 Dashboard Preview

> Add screenshots of your dashboard inside the **Images** folder and update the image path below.

```
Images/Theme 1.png
```

---

## 🎯 What I Learned

This project helped me strengthen my understanding of:

- Connecting Power BI with REST APIs
- Working with JSON data
- Power Query transformations
- Data modeling
- DAX calculations
- Interactive dashboard design
- Real-time data visualization
- API-based reporting solutions

---

## 🔮 Future Enhancements

Some improvements planned for future versions include:

- Hourly weather forecast
- Weather alerts
- Additional cities
- Historical weather analysis
- Automatic scheduled refresh
- Mobile-friendly dashboard layout

---

## 👩‍💻 Author

**Yogita Aggarwal**

**MCA (Artificial Intelligence & Machine Learning)**

**Skills:** Power BI • SQL • Python • Data Analytics • Data Visualization
