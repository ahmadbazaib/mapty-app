# 🗺️ Mapty App

Mapty is a location-based fitness tracking application that lets users log running and cycling workouts directly on an interactive map using Leaflet.js. It stores workout data in the browser's local storage and provides a dynamic and visually engaging interface to review past workouts.

🚀 Live Demo

🔗 [Visit Mapty](#)

---

## 📜 Features

📍 **Geolocation**: Automatically detects user’s location to initialize the map.  
📝 **Log Workouts**: Click on the map to add a running or cycling workout with details like distance, duration, cadence, or elevation.  
🧭 **Map Markers**: Each workout is displayed with a custom popup marker.  
📄 **Workout List**: Logged workouts are listed in a sidebar with contextual data.  
💾 **Persistent Storage**: Workouts are stored using `localStorage` and reloaded on page refresh.  
📍 **Smooth Panning**: Click on a workout to pan the map to its location.

---

## 🛠️ Technologies Used

- **HTML** – Structure and layout of the application
- **CSS** – Styling and responsiveness
- **JavaScript (ES6+)** – Core logic, OOP with classes, event handling, and DOM manipulation
- **Leaflet.js** – Open-source library for interactive maps
- **Geolocation API** – Get user's current coordinates
- **localStorage API** – Persist data between sessions

---

## 🎯 Why This Project?

- To master JavaScript ES6+ (classes, arrow functions, array methods)
- Gain experience integrating third-party libraries (Leaflet.js)
- Practice DOM event handling and form data validation
- Apply OOP principles in building real-world applications

---

## 📌 Future Enhancements

These are additional feature ideas and challenges you can implement to extend the app’s functionality:

- ✏️ Ability to **edit** a workout
- 🗑️ Ability to **delete** a workout
- 🧹 Ability to **delete all** workouts
- 📊 Ability to **sort** workouts by fields (e.g. distance, duration)
- ♻️ **Rebuild** `Running` and `Cycling` class instances from data in localStorage
- ❗ More realistic **error and confirmation messages**
- 🌍 Automatically position the map to **show all workouts** (Very hard)
- 🖍️ Draw **lines and shapes** instead of just points (Very hard)
- 🧭 **Geocode** location from coordinates (e.g. "Run in Faro, Portugal") _(Requires asynchronous JavaScript)_
- 🌦️ **Display weather** for each workout location and time _(Requires asynchronous JavaScript)_

---

## 🧠 Concepts Covered

- Object-Oriented Programming with ES6 Classes
- Using guard clauses and validating user input
- DOM manipulation and event delegation
- Map interaction via Leaflet's API
- Handling `localStorage` for data persistence
- Geolocation and real-world mapping concepts
