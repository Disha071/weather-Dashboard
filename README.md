Weather Application

This project is a React application that allows users to search for cities and view current weather and forecast information using data from OpenWeatherMap and a geo-location database API.

Features
City Search: Users can search for cities by name.
Current Weather: Display current weather information including temperature, weather description, and related details.
7-Day Forecast: Provides a forecast for the upcoming week with daily weather details.
Responsive Design: The application is designed to work well on different screen sizes.
Technologies Used
React
react-select-async-paginate
react-accessible-accordion
CSS (for styling)
APIs Used
OpenWeatherMap API: Used to fetch weather data based on city coordinates.
Geo API (RapidAPI): Used to fetch city information based on user search input.

Explore the live demo: [WeatherNerd Live Demo](https://weathernerd.netlify.app/)

Installation
Clone the repository:

bash
Copy code
git clone https://github.com/ayushchahal44/Weather-dashboard.git
cd repository-name
Install dependencies:

bash
Copy code
npm install
Set up API keys:

Obtain an API key from OpenWeatherMap and update WEATHER_API_KEY in api.js.
Obtain an API key from RapidAPI for the Geo API and update X-RapidAPI-Key in api.js.
Start the development server:

bash
Copy code
npm start
Open the application in your browser at http://localhost:3000.

Usage
Enter a city name in the search bar.
Select a city from the dropdown suggestions.
View the current weather and 7-day forecast for the selected city.


Contributing
Contributions are welcome! If you'd like to contribute to this project, please fork the repository and create a pull request.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
React: https://reactjs.org/
OpenWeatherMap: https://openweathermap.org/
RapidAPI: https://rapidapi.com/
