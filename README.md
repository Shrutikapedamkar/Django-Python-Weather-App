# Weather App using Django and OpenWeatherMap API
![image](https://github.com/Shrutikapedamkar/Django-Python-Weather-App/assets/47322770/b06c76d8-ea69-48a9-bf0a-61cc74b3db5c)

Overview: <br>
This is a basic web application that provides weather updates for any city using Django and the OpenWeatherMap API. Users can search for a city, and the app will display the current weather conditions for that location.

Features <br>
Current weather information: Provides real-time weather data including temperature, humidity, pressure, and weather description.
City search: Users can enter the name of the city they want to get weather information for.

Prerequisites <br>
Before you begin, ensure you have the following requirements installed:
Python (version 3.6 or higher)<br>
Django (version 3.x)<br>
An API key from OpenWeatherMap (free tier available)<br>

#Setup<br>

1. Clone the repository to your local machine:
```
git clone https://github.com/yourusername/weather-app.git
```
2. Navigate to the project directory:
```
cd weather-app
```
3. Configure your OpenWeatherMap API key: <br>
Open the settings.py file in your Django project. <br>
Find the OPENWEATHERMAP_API_KEY variable and replace 'YOUR_API_KEY_HERE' with your actual API key. <br>

4. Migrate the database:
```
python manage.py migrate
```
5. Start the development server:
```
python manage.py runserver
```
6. Visit http://localhost:8000 in your web browser to access the app.
