# 🌤️ Weather App

A responsive React application that displays current weather information for any city in the world.  
It fetches live data from the [OpenWeatherMap API](https://openweathermap.org/api).

---

## 📌 Features
- Search for weather by **city name**.
- Displays:
  - Temperature
  - Weather description
  - Weather icon
- Responsive design for desktop and mobile.
- Built with React and Vite for fast performance.

---

## 🛠️ Tech Stack
- **Frontend:** React, Vite
- **Styling:** CSS
- **API:** [OpenWeatherMap](https://openweathermap.org/) REST API
- **Package Management:** npm

---

## 📦 Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/weather-app.git
   cd weather-app
2. **Create a .env file in the project root:**
   ```env
   VITE_WEATHER_API_KEY=your_api_key_here
3.	**Install dependencies**
    ```bash
  	npm install
4.  **Run the app**
    ```bash
  	npm run dev
4.  **Open in browser**
    ```bash
  	http://localhost:5173

## 🚀 Usage
	1.	Type a city name in the search box.
	2.	Press Enter or click Search.
	3.	View the live weather information.

## 📂 Project Structure
   weather-app/
│── public/             # Static assets
│── src/
│   ├── App.jsx         # Main UI and API logic
│   ├── main.jsx        # React entry point
│   ├── App.css         # Component styles
│   ├── index.css       # Global styles
│   └── assets/         # Images and icons
│── index.html          # Root HTML file
│── package.json        # Project dependencies
│── vite.config.js      # Vite configuration
