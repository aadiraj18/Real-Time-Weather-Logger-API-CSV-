# 🌦️ Real-Time Weather Logger (API + CSV)

A simple Python CLI tool that fetches real-time weather data for a given city and logs it into a CSV file for daily tracking.

---

## 🚀 Features

* 📍 Enter any city name to fetch current weather
* 🌡️ Stores temperature (°C) and weather condition
* 📅 Automatically logs today's date
* 🚫 Prevents duplicate entries (same city, same day)
* 📊 View all stored weather logs
* 💾 Data saved in `weather_logs.csv`

---

## 🛠️ Technologies Used

* Python
* OpenWeatherMap API
* CSV file handling
* Requests library

---

## 📦 Installation

1. Clone the repository:

```bash
git clone https://github.com/aadiraj18/Real-Time-Weather-Logger-API-CSV.git
cd weather-logger
```

2. Install dependencies:

```bash
pip install requests
```

---

## 🔑 API Setup

1. Get your API key from:
   https://openweathermap.org/api

2. Replace this line in the code:

```python
API_KEY = "your_api_key_here"
```

---

## ▶️ How to Run

```bash
python 01_weather_logger.py
```

---

## 📋 Usage

After running the program:

```
Real time weather logger
1. Add weather log
2. View weather log
```

### Option 1: Add weather log

* Enter city name
* Weather data will be fetched and saved

### Option 2: View weather log

* Displays all saved entries

---

## 📁 File Structure

```
weather-logger/
│
├── 01_weather_logger.py
├── weather_logs.csv
└── README.md
```

---

## ⚠️ Notes

* API key may take a few minutes to activate after creation
* Internet connection is required for fetching weather data
* Duplicate entries for the same city and date are prevented

---

## 💡 Future Improvements

* Convert city name to latitude & longitude
* Add weather statistics (average, highest, lowest)
* Improve CLI UI with tables
* Store API key securely using `.env`

---

## 👨‍💻 Author

**Aadi Raj**
B.Tech CSE (Data Science)

---

## ⭐ If you like this project

Give it a star ⭐ on GitHub!

---

# 📊 Weather Data Visualization (Add-on)

This project is an **extension of the main project**:
👉 **Real-Time Weather Logger (API + CSV)**

It visualizes the stored weather data using graphs for better insights and analysis.

---

## 🔗 Related Project

This module works with the data generated from:

**Real-Time Weather Logger (API + CSV)**
➡️ Make sure you have already generated `weather_logs.csv` using that project.

---

## 🚀 Features

* 📈 Line graph for **temperature over time**
* 📊 Bar chart for **weather condition frequency**
* 📅 Uses stored CSV data (`weather_logs.csv`)
* ⚠️ Handles missing or invalid data safely

---

## 🛠️ Technologies Used

* Python 3
* CSV file handling
* Matplotlib (for data visualization)
* Collections (`defaultdict`)

---

## 📂 Project Structure

```
Real-Time-Weather-Logger-API-CSV/
│
├── weather_logger.py              # Main project
├── 02_Graph_with_matplotlib.py   # Visualization script (Add-on)
├── weather_logs.csv               # Generated data
└── README.md
```

---

## ▶️ How to Run

```bash
git clone https://github.com/aadiraj18/Real-Time-Weather-Logger-API-CSV.git
cd Real-Time-Weather-Logger-API-CSV
python 02_Graph_with_matplotlib.py
```

---

## 📊 Output

### 1. Temperature Trend Graph

* Shows how temperature changes over time

### 2. Weather Condition Distribution

* Displays number of days for each condition (Clear, Rain, etc.)

---

## ⚠️ Requirements

```bash
pip install matplotlib
```

---

## 💡 Notes

* This script depends on `weather_logs.csv`
* If no data is present → program will exit safely
* Ensure temperature values are numeric in CSV

---

## ✨ Future Improvements

* Add date-wise filtering
* Save graphs as images
* Use advanced libraries like Pandas/Seaborn
* Create dashboard-style UI

---

## 👨‍💻 Author

**Aadi Raj**
B.Tech CSE (Data Science)

---

## ⭐ Support

If you like this project, consider giving it a star ⭐ on GitHub!

---

