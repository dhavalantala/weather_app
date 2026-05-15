# 🌤️ Weather App

A clean, responsive weather application that fetches real-time weather data using the [OpenWeatherMap API](https://openweathermap.org/api).

🔗 **Live Demo:** [https://dhavalantala.github.io/weather_app/](https://dhavalantala.github.io/weather_app/)

---

## 📸 Preview

The app displays current weather conditions including temperature, humidity, and wind speed, with dynamic icons that change based on weather type.

---

## ✨ Features

- 🔍 Search weather by city name
- 🌡️ Displays current temperature in °C
- 💧 Shows humidity percentage
- 💨 Shows wind speed in km/h
- 🌦️ Dynamic weather icons (Rain, Clouds, Clear, Drizzle, Mist, Snow)
- ❌ Error handling for invalid city names

---

## 🛠️ Tech Stack

| Technology | Usage |
|---|---|
| HTML5 | Structure |
| CSS3 | Styling & layout |
| JavaScript (Vanilla) | Logic & API calls |
| OpenWeatherMap API | Live weather data |

---

## 📁 Project Structure

```
weather_app/
├── index.html       # Main HTML file
├── style.css        # Styles and layout
├── script.js        # JavaScript logic and API integration
├── README.md        # Project documentation
└── images/          # Weather icons
    ├── search.png
    ├── humidity.png
    ├── wind.png
    ├── clouds.png
    ├── clear.png
    ├── drizzle.png
    ├── mist.png
    ├── rain.png
    └── snow.png
```

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/dhavalantala/weather_app.git
cd weather_app
```

### 2. Get an API Key

- Sign up at [https://openweathermap.org/](https://openweathermap.org/)
- Go to **API Keys** in your account dashboard
- Copy your API key

### 3. Add your API Key

Open `script.js` and replace the existing key with yours:

```js
const apiKey = 'YOUR_API_KEY_HERE';
```

### 4. Run the app

Simply open `index.html` in your browser — no build tools or server required.

---

## 🔌 API Reference

This app uses the **OpenWeatherMap Current Weather API**:

```
GET https://api.openweathermap.org/data/2.5/weather?units=metric&q={city}&appid={apiKey}
```

| Parameter | Description |
|---|---|
| `q` | City name |
| `units` | `metric` for Celsius |
| `appid` | Your API key |

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

## 🙋‍♂️ Author

**Dhaval Antala**
- GitHub: [@dhavalantala](https://github.com/dhavalantala)
