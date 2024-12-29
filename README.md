# Weather App

This is a simple weather application built using Python, Tkinter, and OpenWeatherMap API. The app allows users to search for weather information based on the city name. It displays the current weather conditions, including the temperature in Celsius and the weather description.

---

## Features
- **Search Weather by City:** Enter the name of a city to get weather details.
- **Weather Information:** Displays the city, country, temperature in Celsius, and weather condition (e.g., clear sky, rain, etc.).
- **Error Handling:** Shows an error message if the city name is invalid or no data is found.

---

## Tech Stack

- **Python 3.x**
- **Tkinter:** For GUI development
- **requests:** For making HTTP requests to OpenWeatherMap API
- **ConfigParser:** For reading the API key from a configuration file

---

## Configuration

1. Create a file named `config.ini` in the same directory as `app.py`.
2. Add the following content to the `config.ini` file:

   ```ini
   [gfg]
   api = YOUR_API_KEY

---

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/heatblaze/Weather-app.git
  
