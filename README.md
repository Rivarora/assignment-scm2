# 🌟 Weather App

## 📌 Description
The **Weather App** is a web-based application that provides **real-time weather updates**, forecasts, and alerts. It helps users plan their day by offering accurate information on:
- 🌡️ **Temperature**
- 💧 **Humidity**
- 🌬️ **Wind speed**
- 🌦️ **Precipitation**

It offers **easy-to-read visuals** and interactive charts for both current and future weather conditions, ensuring users stay informed and prepared.

---

## 🎯 **Key Features**
✅ **Real-Time Weather Data:** Fetches up-to-date weather information using the **OpenWeatherMap API**.  
📍 **Location Detection:** Automatically detects the user's location using the **Geolocation API**.  
🌤️ **Dynamic Background Images:** The app dynamically changes the background based on the current weather condition.  
📊 **Interactive Charts:** Uses **Chart.js** to display temperature, humidity, and wind speed trends.  
📅 **5-Day Forecast:** Displays a detailed weather forecast for the next 5 days.  
🔍 **Search by City or PIN Code:** Users can search for weather information by entering a city name or a postal code.  
🕰️ **Real-Time Date & Time:** Displays the current date and time.  
💾 **PWA Functionality:** The app can be installed as a **Progressive Web App (PWA)**, allowing offline access.  
🔔 **User-Friendly Alerts:** Displays weather alerts for severe conditions.  
🌐 **Responsive Design:** Optimized for desktop, tablet, and mobile devices.  

---

## 🎨 **Demo Preview**
Here is a simple **HTML & CSS snippet** from the project:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Weather App Demo</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background: linear-gradient(135deg, #74EBD5, #ACB6E5);
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            color: #444;
            margin: 0;
        }
        .container {
            text-align: center;
            background: #ffffff;
            padding: 50px;
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.2);
            border-radius: 12px;
            transition: transform 0.3s, box-shadow 0.3s;
        }
        .container:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 35px rgba(0, 0, 0, 0.3);
        }
        h1 {
            font-size: 2.5rem;
            color: #3498db;
        }
        .btn {
            background: #2ecc71;
            color: white;
            padding: 12px 30px;
            font-size: 18px;
            border: none;
            border-radius: 8px;
            cursor: pointer;
            transition: background 0.3s, transform 0.2s;
        }
        .btn:hover {
            background: #27ae60;
            transform: scale(1.1);
        }
        .collaborators {
            margin-top: 30px;
            font-size: 16px;
            color: #555;
        }
        .collaborators span {
            font-weight: bold;
            color: #2c3e50;
        }
    </style>
</head>
<body>

<div class="container">
    <h1>Weather App Demo 🌦️</h1>
    <button class="btn" onclick="alert('Button Clicked!')">Explore Weather</button>

    <div class="collaborators">
        <p>👥 <span>Collaborators:</span> Ritika, Riva, Tishya, Yakshi</p>
    </div>
</div>

</body>
</html>


