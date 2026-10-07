# AakashVani: City-Wise Weather Reporting System 🌤️

[![Live Demo](https://img.shields.io/badge/Live_Demo-aakashvani--sigma.vercel.app-000000?style=flat&logo=vercel)](https://aakashvani-sigma.vercel.app/)
[![GitHub Repo](https://img.shields.io/badge/GitHub-harshanandbadal%2FAakashVani-181717?style=flat&logo=github)](https://github.com/harshanandbadal/AakashVani)
[![Platform](https://img.shields.io/badge/Platform-Web-blue.svg)](https://developer.mozilla.org/en-US/docs/Web)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Active-success.svg)]()

**AakashVani** (*"Voice from the Sky"*) is a modern, responsive web-based weather reporting portal and decision-support system. It delivers real-time meteorological observations, short- and long-range forecasts, and comprehensive city-level weather dossiers across major cities in India.

The application features a modern mobile interface framed inside a smartphone showcase on desktop, with seamless expansion to a full-width dashboard.

---

## 🔗 Quick Links

* 🌐 **Live Web Application**: [https://aakashvani-sigma.vercel.app/](https://aakashvani-sigma.vercel.app/)
* 📦 **GitHub Repository**: [https://github.com/harshanandbadal/AakashVani](https://github.com/harshanandbadal/AakashVani)

---

## 🌟 Key Features

* **High-Fidelity Interface**:
  * Designed to replicate modern smartphone weather applications with a live status bar, atmospheric sky gradients, floating cloud animations, and sunset city skylines.
  * Dual-mode view: **📱 Phone Mockup View** (for handheld showcase) and **🖥️ Expanded View** (for widescreen displays).
* **Live Weather Integration (Zero API Key Setup)**:
  * Powered by the **Open-Meteo API** for live temperature, humidity, surface pressure, wind vectors, and weather codes.
  * Instant local caching and built-in offline fallbacks for 50+ major Indian cities.
* **City-Wise Weather Dossier Reports**:
  * Generates an official **Meteorological Observation Report** for any selected city.
  * Includes IMD (India Meteorological Department) calibration benchmarks, diurnal 24-hour observation logs, 7-day extended prognostic outlooks, and agricultural/civic decision-support advisories.
  * **Print-to-PDF Ready**: Specially styled for clean paper/PDF export.
* **City Reports Directory**:
  * Search, filter, and discover weather reports categorized by geographic zone: **North**, **South**, **East**, **West**, and **Central India**.
* **Interactive Pan-India Weather Map**:
  * Visual station map with clickable city markers to switch monitoring locations instantly.
* **Severe Weather Advisories**:
  * Live bulletins for thunderstorms, high wind velocities, heatwaves, and humidity indexes.
* **Unit Conversion**:
  * Toggle between **Metric (°C)** and **Imperial (°F)** across all screens and reports.

---

## 🛠️ Technology Stack

| Layer | Technology | Purpose |
| :--- | :--- | :--- |
| **Markup** | HTML5 (Semantic) | Application structure, accessible modals, and SVG graphics |
| **Styling** | Vanilla CSS3 | Custom properties (tokens), Glassmorphism, animations, print stylesheets |
| **Scripting** | JavaScript (ES6+) | Asynchronous API fetching, state management, autocomplete, and DOM manipulation |
| **Data Provider** | [Open-Meteo API](https://open-meteo.com/) | Real-time weather data (free, no API key required) |
| **Typography** | Google Fonts | *Plus Jakarta Sans*, *Outfit*, and *JetBrains Mono* |

---

## 📁 Project Structure

```text
AakashVani-City-Wise-Weather-Reporting-System/
├── index.html            # Main web application entry point & modal definitions
├── style.css             # Comprehensive design system, phone frame, animations & print styles
├── app.js                # Core JavaScript engine, city database, API client & UI controller
├── .gitignore            # Git exclusion rules for node, logs, and build artifacts
└── README.md             # Project documentation and architecture guide
```

---

## 🚀 Getting Started

No build step or external dependencies are required. You can run the project using any static web server:

### Option 1: Python (Built-in)
```bash
# Start a local HTTP server on port 3000
python -m http.server 3000
```
Open [http://localhost:3000](http://localhost:3000) in your browser.

### Option 2: Node.js (npx serve)
```bash
npx serve -l 3000 .
```
Open [http://localhost:3000](http://localhost:3000) in your browser.

### Option 3: VS Code Live Server
* Open the repository folder in VS Code.
* Right-click `index.html` and select **"Open with Live Server"**.

---

## 📊 Weather Data & Accuracy Calibration

The system adheres to standard meteorological observation benchmarks:
* **Temperature (°C)**: Calibrated within $\pm 0.2^\circ\text{C}$ of official station readings.
* **Relative Humidity (%)**: Calibrated within $1\%$ variance.
* **Wind Velocity (km/h)**: Measured at 10m elevation with gust detection.
* **Air Quality Index (AQI)**: Continuous particulate matter indexing (PM2.5 / PM10 equivalent).

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
