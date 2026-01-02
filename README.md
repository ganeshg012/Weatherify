# Weatherify – Real-Time Weather App

**Weatherify** is a responsive web application that lets users search for current weather information for any city in the world. It’s built using **HTML, CSS, and JavaScript** with integration to the **OpenWeatherMap API** for real-time weather data. :contentReference[oaicite:1]{index=1}

## 🌦️ Features

- 🔍 **City Weather Search** – Enter any city name to fetch live weather details. :contentReference[oaicite:2]{index=2}  
- 🌡️ **Weather Data Display** – Shows temperature, humidity, wind speed, and general conditions like sunny, cloudy, or rainy. :contentReference[oaicite:3]{index=3}  
- 📊 **Dynamic UI Updates** – Weather information updates instantly based on API response. :contentReference[oaicite:4]{index=4}  
- 🗂️ **Add / Edit / Delete Tasks UI Logic** – Includes JavaScript-powered task item UI interactions (add/edit/delete) to demonstrate DOM manipulation.  
- 📱 **Responsive Design** – Optimized for both desktop and mobile screen sizes.

## 🛠️ Technologies Used

- **HTML** – Page structure and content.  
- **CSS** – Styling for layouts, cards, and responsiveness.  
- **JavaScript** – DOM manipulation, API calls, and logic for weather data and task UI interactions.

## 🚀 Live Demo

🔗 Visit the live application here:  
👉 https://ganeshg012.github.io/weatherify/

## 📦 How It Works

1. **Search by City**  
   Users type a city name into the search field and hit submit. JavaScript sends a `fetch` request to the OpenWeatherMap API with that city name. :contentReference[oaicite:5]{index=5}

2. **API Response Handling**  
   The app receives JSON weather data (temperature, humidity, wind, etc.) and updates the UI elements dynamically using DOM manipulation. :contentReference[oaicite:6]{index=6}

3. **Task UI Logic**  
   The app includes a small interactive task list component that allows users to add, edit, and delete tasks purely on the frontend using JavaScript event listeners and DOM updates.

## 🧪 Setup & Usage

1. Clone the project:
   ```bash
   git clone https://github.com/ganeshg012/weatherify.git
