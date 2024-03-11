## Overview

This simple web application fetches weather data from OpenWeatherMap API based on user input or the user's geolocation. It dynamically updates the background image of the webpage using the Unsplash API and incorporates the OpenCageData Geocoder API for reverse-geocoding.

## Features
   
1. **OpenWeatherMap Integration:** 
## App link: `https://mohamedhathil.github.io/weatherapp/`
   - The code fetches weather data from OpenWeatherMap using a provided API key.
   - The `fetchWeather` function takes a city as input, sends a request, and displays the weather data on the webpage.

2. **Dynamic Background Image:**
   - The background image of the webpage changes dynamically based on the searched city, utilizing the Unsplash API.

3. **OpenCageData Geocoder Integration:**
   - The code uses the OpenCageData Geocoder API to reverse-geocode latitude and longitude to obtain the city name.

4. **Geolocation Retrieval:**
   - The `getLocation` method attempts to get the user's current location using the `navigator.geolocation` API.

5. **Error Handling:**
   - The code handles errors during API requests, logging messages to the console in case of unsuccessful responses.

6. **Event Listeners:**
   - Event listeners are set up to trigger the weather search when the search button is clicked or the Enter key is pressed in the search bar.

7. **Initial Weather Fetch:**
   - The code initiates an initial weather fetch for the city "tamilnadu" when the page loads.

8. **Asynchronous Programming:**
   - Promises are used for asynchronous handling of API responses, ensuring a smooth flow of data retrieval and display.

9. **Modular Structure:**
   - The code is organized into two main objects (`weather` and `geocode`), promoting modularity and maintainability.

10. **Fallback for Geolocation:**
    - If geolocation is not supported or unsuccessful, the code defaults to fetching weather data for the city "tamilnadu."
