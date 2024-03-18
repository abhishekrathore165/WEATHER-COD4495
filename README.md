Task- Two Weather App using HTML CSS JAVASCRIPT ?

 HTML Structure:

    The HTML structure consists of a container (<div class="card">) containing elements for displaying weather information.
    Inside the container, there's a search bar (<div class="search">) with an input field and a search button.
    Below the search bar, there's a section to display any errors (<div class="error">) if the entered city is invalid.
    Finally, there's a section to display weather information (<div class="weather">), including the city name, temperature, weather icon, humidity, and wind speed.

CSS Styling:

    The CSS file (style.css) contains styles to give the application a visually appealing look.
    It sets up the layout, colors, fonts, and spacing for various elements in the application.

JavaScript Functionality:

    The JavaScript file (script.js) is responsible for fetching weather data from the OpenWeatherMap API and updating the UI accordingly.
    It listens for a click event on the search button (searchbtn), then calls the checkWeather function.
    The checkWeather function performs an asynchronous fetch request to the OpenWeatherMap API using the provided city name.
    If the city is found, it updates the UI with the fetched weather data, including the city name, temperature, humidity, wind speed, and an appropriate weather icon based on the weather conditions.
    If the city is not found (404 status), it displays an error message indicating an invalid city name.

OpenWeatherMap API:

    The application utilizes the OpenWeatherMap API to fetch current weather data for the specified city.
    It uses a provided API key (apikey) and constructs the API request URL based on the city name entered by the user.

Project Overview:

    This weather application provides a simple and intuitive interface for users to check the current weather conditions of any city.
    It leverages modern web technologies to fetch and display real-time weather information dynamically.
    The project demonstrates basic concepts of web development, including API integration, DOM manipulation, and event handling.
    With its clean and responsive design, the application offers a seamless user experience across different devices and screen sizes.
