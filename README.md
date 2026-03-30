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
git clone https://github.com/your-username/weather-logger.git
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
API_KEY = "c6048d32493ec1fada776b7eb9a225ed"
```

---

## ▶️ How to Run

```bash
python day_4.py
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
├── weather_logger.py
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
