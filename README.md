# Weather App

## Description
This Weather App is a simple, user-friendly application that provides real-time weather information for any location around the world. Built with HTML, CSS, and JavaScript, it allows users to input a city name and get detailed weather information, such as temperature, humidity, wind speed, and a short description of the weather conditions.

## Features
- Search weather information by city name
- Display real-time weather data including temperature, humidity, wind speed, and weather description
- Dynamic and responsive UI for an enhanced user experience
- Clear and minimalistic design for easy navigation
-visit site ----> https://conditionweather.netlify.app/
## Technologies Used
- **HTML**: For structuring the application layout
- **CSS**: For styling and designing the interface
- **JavaScript**: For adding interactivity and fetching real-time weather data using APIs

## Installation and Usage

### Prerequisites
- A modern web browser
- An active internet connection
- A free API key from [OpenWeatherMap](https://openweathermap.org/api)

### Steps to Run the App
1. Clone the repository to your local machine:
   ```bash
   git clone <repository-url>
   ```

2. Navigate to the project directory:
   ```bash
   cd weather-app
   ```

3. Open the `index.html` file in your preferred browser:
   ```
   Open with a web browser.
   ```

4. Input a city name in the search bar and click the search button to get the weather details.

## API Integration
This app uses the [OpenWeatherMap API](https://openweathermap.org/api) to fetch real-time weather data. To use the app, you'll need to sign up for an API key and update the JavaScript file with your key.

### How to Update the API Key
1. Sign up at [OpenWeatherMap](https://openweathermap.org/) and get your free API key.
2. Locate the section in the JavaScript file where the API key is defined:
   ```javascript
   const apiKey = 'your_api_key_here';
   ```
3. Replace `'your_api_key_here'` with your actual API key.

## Folder Structure
```
weather-app/
├── index.html        # Main HTML file
├── style.css         # CSS for styling the app
├── script.js         # JavaScript for functionality
└── README.md         # Documentation
```

## Future Enhancements
- Add geolocation support to detect the user’s current location
- Display a 7-day weather forecast
- Provide an option to switch between Celsius and Fahrenheit
- Add animations for a better visual experience

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

## Acknowledgements
- [OpenWeatherMap API](https://openweathermap.org/)
- [MDN Web Docs](https://developer.mozilla.org/) for web development resources

---

Enjoy exploring the weather around the world with this app! If you encounter any issues or have suggestions for improvements, feel free to create an issue or submit a pull request.

