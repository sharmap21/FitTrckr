# 🏃‍♂️ FitTrackr 🗺️

**FitTrackr** is a responsive web application that allows users to log and visualize their running and cycling workouts on an interactive map. It leverages geolocation, Leaflet.js, and localStorage to provide a smooth, client-side fitness tracking experience.


---

## 🚀 Features

- 📍 **Real-time Geolocation**: Automatically centers the map based on your current location.
- 🏃‍♂️ **Activity Logging**: Log workouts by clicking on the map. Supports:
  - Running (with pace & cadence)
  - Cycling (with speed & elevation)
- 💾 **Persistent Data**: All workout data is saved in `localStorage` — reload without losing history.
- 🗂️ **Responsive Design**: Optimized for mobile, tablet, and desktop.
- 🌍 **Interactive Map**: View workout markers and move to their location with one click.

---

## 🛠️ Tech Stack

- **HTML5 / CSS3** – Semantic structure and custom responsive styling
- **JavaScript (ES6+)** – Class-based OOP and DOM manipulation
- **Leaflet.js** – Map and marker rendering
- **localStorage API** – Save and retrieve workouts client-side

---

## 📌 How to Use

1. **Open `index.html`** in your browser.
2. Click **"Get Started"** to launch the workout tracker.
3. Allow location access when prompted.
4. Click on the map to log a new workout.
5. Fill in workout details and hit Enter.
6. View your workouts listed and mapped.
7. Use the **RESET** button to clear all stored workouts.

---

## 🔧 Setup & Run

This is a static app — no installation required. Just clone and open in browser:

```bash
git clone https://github.com/yourusername/FitTrackr.git
cd FitTrackr
# Open index.html with Live Server or in any modern browser
```

## 📦 To Do / Future Enhancements
- Export workouts to JSON or CSV
- Add filters (e.g., by date or activity type)
- Include charts for performance tracking
- Integrate with fitness APIs or wearables
- Add offline PWA support
  
---

## 🧠 Learnings
This project was built to practice:
- OOP in JavaScript
- DOM manipulation
- Responsive design with media queries
- Real-world use of localStorage and third-party libraries (Leaflet)

---

> Live Demo: https://fascinating-praline-352371.netlify.app/

---

## 📄 License
This project is for educational purposes only. No commercial use intended.
