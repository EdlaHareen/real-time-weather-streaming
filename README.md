# real-time-weather-streaming

# 🌦️ Real-Time Weather Streaming & Live Dashboard using Microsoft Fabric

This project is a complete **end-to-end real-time weather monitoring system** that collects live weather and air quality data for **Chennai**, streams it through **Azure services**, and visualizes it with a dynamic dashboard built in **Power BI (Microsoft Fabric)**.

---

## 🚀 What This Project Does

✅ Fetches live weather & air quality data every 30 seconds  
✅ Sends data to Azure Event Hub via Azure Function  
✅ Streams data in real-time to Microsoft Fabric using Kusto/Event Streams  
✅ Builds a responsive, live Power BI dashboard  
✅ Secures credentials using Azure Key Vault  
✅ Visualizes key weather metrics like temperature, humidity, conditions, and air quality  

---

## 🛠️ Tech Stack

| Component | Purpose |
|----------|---------|
| **Azure Function (Python)** | Fetches data from [WeatherAPI.com](https://www.weatherapi.com/) |
| **Azure Key Vault** | Stores the API key securely |
| **Azure Event Hub** | Streams live data |
| **Microsoft Fabric** | Real-Time Analytics + Power BI |
| **Kusto Query Language (KQL)** | Used to clean/query the data |
| **Power BI (Fabric)** | Final dashboard visualization |

---

## 📊 Power BI Dashboard Features

- 📍 Real-time data for **Chennai**
- 🌡️ **Temperature & humidity trend** (Area Chart)
- 🌥️ **Weather condition breakdown** (Donut Chart)
- 🔁 **Weather condition frequency** over time (Ribbon Chart)
- 📈 Pie chart showing **humidity range distribution**
- 📌 Auto-refreshing visuals every 30 seconds

---

## 📁 Project Structure

```plaintext
weather-streaming-fabric-dashboard/
├── azure-function/           # Azure Function code (Python)
├── queries/                  # Kusto queries used in Fabric
├── dashboard/
│   ├── screenshots/          # Dashboard screenshots
│   └── dashboard-description.md
├── assets/                   # Architecture diagrams and visuals
├── README.md                 # You're here!
└── requirements.txt          # Python dependencies
