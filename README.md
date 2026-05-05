# 🌦️ Weather Forecast Web Application

A sleek and responsive weather application that provides real-time weather updates for any city globally. This project leverages modern web technologies and the OpenWeatherMap API to deliver accurate weather data through a clean, user-friendly interface.

## 🚀 Live Demo
Check out the live application here: [Weather App Demo](https://vins254.github.io/Weather-Application-/)

---

## ✨ Features

- **🔍 Global Search**: Get instant weather updates for any city by entering its name.
- **📍 Geolocation Support**: Automatically detect and display weather for your current location with a single click.
- **📊 Detailed Metrics**: View essential weather data including:
  - Current Temperature (Celsius)
  - Weather Condition (e.g., Clear, Clouds, Rain)
  - "Feels Like" Temperature
  - Humidity Percentage
- **🎨 Dynamic UI**: Interactive interface with custom weather icons that change based on current conditions (Clear, Storm, Snow, Haze, Cloud, Rain).
- **⚠️ Error Handling**: Robust feedback for invalid city names or connectivity issues.

---

## 🛠️ Tech Stack

- **HTML5**: Semantic structure for a modern web layout.
- **CSS3**: Custom styling with a focus on responsiveness, using Flexbox and Google Fonts (Poppins).
- **JavaScript (ES6)**: 
  - Asynchronous data fetching with the **Fetch API**.
  - **Geolocation API** for user position tracking.
  - Dynamic DOM manipulation for real-time updates.
- **OpenWeatherMap API**: The reliable engine powering the weather data.
- **Boxicons**: Premium web icons for enhanced UI aesthetics.

---

## 📖 How It Works

1.  **Input Phase**: The user enters a city name in the input field or triggers the geolocation button.
2.  **API Request**: `script.js` processes the request and sends an asynchronous call to the OpenWeatherMap API using a secure API key.
3.  **Data Processing**: The application parses the JSON response, extracting temperature, humidity, and weather condition IDs.
4.  **UI Update**: 
    - The application dynamically maps weather IDs to custom SVG icons.
    - DOM elements are updated with the latest weather metrics.
    - The interface transitions smoothly to display the weather details.

---

## ⚙️ Installation & Setup

To run this project locally on your machine:

1.  **Clone the Repository**:
    ```bash
    git clone https://github.com/vins254/Weather-Application-.git
    ```
2.  **Navigate to the Directory**:
    ```bash
    cd Weather-Application-
    ```
3.  **Launch the App**:
    Open `index.html` in any modern web browser (Chrome, Firefox, Edge, Safari).

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repository and submit pull requests to improve the design or add new features.

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
