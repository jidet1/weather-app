# 🌦️ Weather App

A simple Django-based web application that allows users to check the current weather of any city using the OpenWeatherMap API.

## 🚀 Features

- Search for any city to get:
  - Temperature (converted to Celsius)
  - Country code
  - Coordinates (longitude & latitude)
  - Humidity
- Clean and responsive UI with Bootstrap 5
- Uses real-time data from OpenWeatherMap API

## 🛠️ Technologies Used

- **Backend:** Python, Django
- **Frontend:** HTML, Bootstrap 5
- **API:** OpenWeatherMap

## 📦 Installation

Follow these steps to run the project locally:

### 1. Clone the repository
    git clone https://github.com/your-username/weather-app.git
    cd weather-app

### 2. Create and activate a virtual environment
    python -m venv venv
    # On Windows
    venv\Scripts\activate
    # On macOS/Linux
    source venv/bin/activate

### 3. Install dependencies
      pip install django requests
      
### 4.  Run migrations
      python manage.py migrate

### 5. Start the development server
      python manage.py runserver

### 6. Then visit: http://127.0.0.1:8000


## ⚙️ Configuration
  The app uses the OpenWeatherMap API. The API key is currently hardcoded in views.py. For production or safety, store the API key in environment variables or a settings.py constant.
  
    appid=2bc0a23ae16a649db7981c44d0812078
    
  💡 You can get your own API key for free at openweathermap.org


## 📁 Project Structure

    weather-app/
    ├── weather/             # Django app
    │   ├── templates/
    │   │   └── weather.html
    │   ├── views.py
    ├── weather_app/         # Project configuration
    │   └── settings.py
    ├── manage.py
    └── requirements.txt     # Optional: use pip freeze > requirements.txt

## 🖼️ Preview
Here’s how the app looks:
![Alt text](app)

## 📄 License
This project is open source under the MIT License
