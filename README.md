# 🌤️ WeatherBot — Dialogflow + OpenWeatherMap

A simple chatbot built with **Python (Flask)**, integrated with **Google Dialogflow** and **OpenWeatherMap API** to provide real-time weather updates.

## 🔗 Repo

**GitHub:** [WeatherBot_DialogFlow](https://github.com/Abs-Futy7/WeatherBot_DialogfLow)

---

## 🚀 Features

- Natural language queries via Dialogflow  
- Real-time weather from OpenWeatherMap  
- Flask webhook handling  
- Lightweight & easy to deploy  

---

## 🛠 Setup

```bash
git clone https://github.com/Abs-Futy7/WeatherBot_DialogfLow.git
cd WeatherBot_DialogfLow
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
pip install -r requirements.txt

```
### Add your OpenWeatherMap API key in ```weather_data.py.```

### Run the server:

```python app.py```

## 🤖 Dialogflow

    Create a Dialogflow agent.

    Add an intent like ask_weather.

    Enable webhook and link to your Flask app (use ngrok for local testing).

    Extract city name with the geo-city entity.

### 🧪 Sample Request

```{ "geo-city": "Dhaka" }

Response:
The current weather in Dhaka is 30°C with scattered clouds.
```
## 👤 Author

**Abs-Futy7**

MIT License


---

Let me know if you want to add badges (like build status or API usage), or make it look great for GitHub 
