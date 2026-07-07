# 🌦️ Weather Forecast Dashboard (Power BI)

## 📌 Project Overview

This project is an interactive Weather Forecast Dashboard developed in **Microsoft Power BI** using live weather data fetched from **WeatherAPI.com**.

The dashboard displays current weather conditions and a 3-day weather forecast for multiple cities. It uses JSON responses from the WeatherAPI service, transforms the data using Power Query, and visualizes it through interactive Power BI reports.

The dashboard automatically updates the displayed weather information based on the selected city.

---

# Features

- 🌍 Weather information for **6 different cities**
- 🌡️ Current Temperature
- 📅 Current Date
- 🏙️ City Selection
- 💧 Humidity
- 🌬️ Wind Speed
- ☁️ Weather Condition
- 🌅 Sunrise
- 🌇 Sunset
- 🌧️ Chance of Rain
- 🌫️ Air Quality Information (PM10)
- 📈 Three-Day Weather Forecast
- Interactive Power BI visuals
- Dynamic filtering based on selected city

---

# Cities Included

- Bangalore
- Gurgaon
- Mumbai
- Lucknow
- Hyderabad
- Noida

---

# Data Source

Weather data is retrieved from:

https://www.weatherapi.com/

The API returns weather information in **JSON format**, which is consumed directly in Power BI using Power Query.

Example endpoint:

```
https://api.weatherapi.com/v1/forecast.json
```

---

# Technologies Used

- Microsoft Power BI
- Power Query (M Language)
- JSON
- WeatherAPI
- DAX
- Data Modeling

---

# Dashboard Components

### Current Weather

Displays:

- Current Temperature
- Weather Condition
- Feels Like Temperature
- Humidity
- Wind Speed
- Air Quality
- Last Updated Time

---

### Forecast

Displays:

- Maximum Temperature
- Minimum Temperature
- Average Temperature
- Chance of Rain
- Daily Weather Condition
- Weather Icons
- Three-Day Forecast

---

### Air Quality

Shows:

- PM10
- AQI Status
- Dynamic Color Indicators

---

### Dynamic Date

The dashboard automatically displays the **current date** corresponding to the selected weather data.

---

# Data Processing

The project follows the following workflow:

1. Connect to WeatherAPI.
2. Fetch weather data in JSON format.
3. Parse nested JSON objects.
4. Transform data using Power Query.
5. Create relationships between forecast and current weather data.
6. Build DAX measures.
7. Design interactive visuals.
8. Publish dashboard.

---

# Power Query Transformations

The JSON response was transformed by:

- Expanding nested records
- Extracting forecast data
- Extracting current weather
- Extracting air quality
- Converting data types
- Creating custom columns
- Removing unnecessary fields

---

# DAX Measures

Some custom DAX measures include:

- Current Date
- AQI Color
- PM10 Status
- Temperature Formatting
- Forecast Labels

---

# Project Workflow

WeatherAPI

↓

JSON Response

↓

Power Query

↓

Data Cleaning

↓

Data Model

↓

DAX Measures

↓

Power BI Dashboard

---

# Dashboard Preview

Example:

```
images/Theme 1.png
```

---

# Future Improvements

- Hourly Forecast
- Weather Alerts
- AQI Prediction
- Additional Cities
- Historical Weather Analysis
- Mobile Optimized Dashboard

---

# Learning Outcomes

Through this project I learned:

- API Integration in Power BI
- Working with JSON data
- Power Query transformations
- DAX calculations
- Dashboard Design
- Dynamic Filtering
- Weather Data Visualization
- Air Quality Visualization

---

# Author

**Yogita Aggarwal**

MCA (Artificial Intelligence & Machine Learning)

Power BI | SQL | Python | Data Analytics
