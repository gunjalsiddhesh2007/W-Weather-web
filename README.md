# W weather — A Daily Field Report

> A considered, editorial daily view of weather, air quality, and atmospheric conditions around you.

![W weather preview](https://img.shields.io/badge/status-active-brightgreen)
![Vanilla JS](https://img.shields.io/badge/javascript-ES6%2B-yellow)
![CSS3](https://img.shields.io/badge/css3-modern-blue)
![License](https://img.shields.io/badge/license-MIT-informational)

---

## ✦ Overview

**W weather** is a lightweight, responsive, editorial-style weather and air-quality web application built with vanilla web technologies. It fetches live meteorological data and forecasts directly from [Open-Meteo](https://open-meteo.com/) without requiring an API key.

## ✨ Features

- **Live Local Conditions**: Current temperature, feels-like temperature, dynamic weather descriptions, high/low range, and sunrise/sunset times.
- **Hourly Forecast**: 12-hour horizontal timeline with temperature, weather iconography, and precipitation probabilities.
- **Air Quality & Atmospheric Vitals**: US AQI reading with advisory badges, PM2.5, PM10, and UV index.
- **5-Day Outlook**: Clean tabular forecast showing day-by-day temperatures and condition glyphs.
- **Field Notes**: Quick glances at wind speed/direction, relative humidity, peak UV index, and chance of rain.
- **Instant Search & Geocoding**: Search for any city worldwide with debounced auto-complete suggestions.
- **Geolocation Support**: Detect your current position with a single click.
- **Unit Toggle**: Effortless switching between Celsius (°C) and Fahrenheit (°F).
- **Smooth Editorial Design**: Clean dark aesthetic, fluid responsive layout, and scroll-reveal transitions.
- **Zero Dependencies**: Pure HTML5, modern CSS3, and vanilla ES6+ JavaScript. No build step or package manager required.

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/<your-username>/weather.git
cd weather
```

### 2. Run locally
Since the app consists of static files with no build process, you can run it in multiple ways:

- **Directly in your browser**: Double-click [index.html](file:///c:/Users/Admin/Downloads/weather/index.html) to open it.
- **Using a local server (recommended for geolocation & fetch)**:
  ```bash
  # Using Python 3
  python -m http.server 8000

  # Or using Node.js npx
  npx serve .
  ```
  Then navigate to `http://localhost:8000`.

---

## 🌐 Deploying to GitHub Pages

You can host this project for free on **GitHub Pages**:

1. Push your repository to GitHub.
2. In your GitHub repository, go to **Settings** > **Pages**.
3. Under **Branch**, select `main` (or `master`) and folder `/ (root)`.
4. Click **Save**.
5. Your weather app will be live at `https://<your-username>.github.io/<repo-name>/`!

---

## 📁 Project Structure

```text
├── index.html        # Semantic HTML5 markup
├── style.css         # Modern responsive CSS & custom properties
├── script.js         # Weather & air quality client logic (Open-Meteo)
├── .gitignore        # Git ignore rules for clean commits
└── README.md         # Project documentation
```

---

## 📡 Data & Attributions

- Weather and Geocoding APIs powered by [Open-Meteo](https://open-meteo.com/) (Free for non-commercial use, no API key needed).
- Typography via Google Fonts: [Manrope](https://fonts.google.com/specimen/Manrope), [DM Sans](https://fonts.google.com/specimen/DM+Sans), and [DM Mono](https://fonts.google.com/specimen/DM+Mono).

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
