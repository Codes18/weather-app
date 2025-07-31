Here is a **single-page README-style explanation** of your weather app — clear, simple, and suitable for quick reference or submission:

---

# 🌤️ Weather App (Single Page Overview)

This is a simple weather forecast web app that lets users check the current weather of any city using the **OpenWeatherMap API**.

---

## 🔹 Features:

* 🌆 Search weather by city name
* 🌡️ Displays temperature (°C)
* 💧 Shows humidity level
* 🌬️ Shows wind speed
* 🌥️ Weather icon changes based on condition (Rain, Clouds, Mist, etc.)
* ⚠️ Error message if city not found

---

## 🔹 Technologies Used:

* HTML
* CSS
* JavaScript (ES6)
* OpenWeatherMap API

---

## 🔹 How It Works:

1. User enters a city name in the input box.
2. JavaScript fetches data from OpenWeatherMap API using `fetch()`.
3. The app extracts:

   * Temperature → `.temp`
   * Humidity → `.humidiyt`
   * Wind speed → `.wind`
   * City name → `.city`
4. Displays corresponding icon based on weather condition (like `"Clouds"`, `"Rain"`, `"Clear"` etc.).
5. If city is invalid (404 error), shows the error message and hides weather info.

---

## 🔹 Folder Structure:

```
project/
├── index.html
├── assets/
│   ├── css/
│   │   └── style.css
│   └── img/
│       ├── rain.png
│       ├── clouds.png
│       ├── clear.png
│       ├── mist.png
│       ├── wind.png
│       ├── humidity.png
│       └── search.png
```

---

## 🔹 Setup Steps:

1. Get a free API key from [https://openweathermap.org/api](https://openweathermap.org/api)
2. Replace this in your script:

   ```js
   const apikey = "your_api_key_here";
   ```
3. Open `index.html` in a browser.
4. Type any city and click the search icon.

---

## 🔹 Example API URL:

```
https://api.openweathermap.org/data/2.5/weather?units=metric&q=Delhi&appid=your_api_key
```

---

## 🔹 Notes:

* Make sure image paths are correct.
* Weather condition (`data.weather[0].main`) is used to switch icons.
* Input is case-insensitive.
* City not found → displays error (`.error` block shown).

---

Let me know if you'd like a **printable PDF version** or if you want the same in **Hindi**.
