# Weather App

This is a simple weather app that allows users to check the current weather conditions of any city. The app fetches real-time weather data from the OpenWeather API and displays it to the user, including temperature, humidity, and wind speed, along with a relevant weather icon.

## Features

- Enter a city name to check its weather.
- Displays current temperature, humidity, and wind speed.
- Shows a weather icon based on the weather conditions (e.g., sunny, cloudy, rainy).
- Error handling for invalid city names.

## Technologies Used

- HTML
- CSS
- JavaScript
- OpenWeather API (for fetching weather data)

## API Key

This project uses the OpenWeather API to fetch weather data. You will need to replace the `apiKey` in the JavaScript file with your own API key. You can get an API key by signing up at [OpenWeather](https://openweathermap.org/).
`` javascript
const apiKey = "YOUR_API_KEY";
## File Structure
index.html: The main HTML file that contains the structure of the weather app.
style.css: The CSS file that styles the weather app.
images/: Folder containing images for weather icons (e.g., clear, clouds, rain).
script.js: JavaScript file that handles API requests, data processing, and UI updates.
## Installation
1.Clone this repository to your local machine:
bash
Copy code
git clone https://github.com/yourusername/weather-app.git
2.Open index.html in your browser to use the app.
## Usage
Open the app in your browser.
Type the name of a city in the search input field.
Press the search button or hit "Enter" to fetch the weather details.
The app will display the current temperature, humidity, wind speed, and a weather icon based on the conditions.
## Error Handling
If the user enters an invalid city name or if there is an issue with the API request, an error message will be displayed.
## License
This project is open source and available under the MIT License.
