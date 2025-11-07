
# 🌦️ Wide Weather + Time Widget

A responsive weather and time widget with dynamic background effects (rain, snow, fog, thunder) and intensity, supporting city search and geolocation.

---

## 🚀 Features

- **Dynamic weather background**: Clear, cloudy, rain, snow, fog, thunder, with animated effects.
- **City search**: Search weather by city name (e.g., Seoul, Tokyo, New York).
- **Geolocation**: Get weather for your current location.
- **Unit toggle**: Switch between Celsius (℃) and Fahrenheit (℉).
- **Live clock**: Shows local date and time for the selected city.
- **3-day forecast**: Displays weather icons and high/low temperatures.
- **Responsive design**: Works on desktop and mobile.

---

## 🖥️ Usage

1. **Open the HTML file in your browser.**
2. **Search** for a city or use **내 위치** (My Location) to get local weather.
3. Toggle between **℃** and **℉** as needed.

---

## 📝 UI Overview

- **Search bar**: Enter a city name and click "검색" (Search) or press Enter.
- **내 위치**: Use browser geolocation to get weather for your current location.
- **℃ / ℉**: Switch temperature units (now vertically aligned).
- **Weather icon & description**: Shows current weather.
- **Live clock**: Local time and date for the selected city.
- **Details**: Feels like, wind speed, humidity, today's high/low.
- **Forecast**: Next 3 days' weather.
- **Note**: Fun message and error display.

---

## 📁 Directory Structure

```
/project-root/
├── weather_widget.html   # Main HTML file (this widget)
└── (no dependencies, all-in-one)
```

---

## ⚙️ Customization

- **Default city**: Set in the script section (`loadByQuery("Seoul")`).
- **Button size**: Controlled via CSS (`font-size: 0.85em; padding: 8px 9px;`).
- **Unit buttons**: Now vertically aligned and top-aligned with search buttons.

---

## 🖌️ Styling

- All styles are in the `<style>` tag in the HTML head.
- Weather effects use CSS variables for easy adjustment.
- Responsive for both desktop and mobile.

---

## 🛠️ Requirements

- Modern web browser (Chrome, Edge, Firefox, Safari, etc.)
- Internet connection (for weather/geocoding API)


