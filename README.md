###  Weather App Project

**Project Name:** Weather App

**Description:**
The Weather App is a simple and intuitive web application designed to provide users with real-time weather information based on their location input. The app uses the OpenWeatherMap API to fetch and display weather data, including temperature, weather conditions, humidity, and wind speed.

**Features:**
1. **Location-based Search:** Users can enter the name of their city to retrieve current weather information.
2. **Weather Display:** The app displays the weather condition with corresponding icons for clear, rain, snow, clouds, and haze.
3. **Temperature:** Shows the current temperature in Celsius.
4. **Description:** Provides a textual description of the weather conditions.
5. **Humidity:** Displays the current humidity level.
6. **Wind Speed:** Indicates the wind speed in kilometers per hour.
7. **Error Handling:** If an invalid location is entered, the app displays an error message.

**Technologies Used:**
- **HTML:** For structuring the web page.
- **CSS:** For styling the app and creating a responsive design.
- **JavaScript:** For making API calls and updating the DOM with the fetched weather data.
- **OpenWeatherMap API:** For retrieving current weather information.
- **Font Awesome:** For using icons representing location, search, water (humidity), and wind.

**Project Structure:**
- `index.html`: The main HTML file that contains the structure of the app.
- `style_1.css`: The CSS file that styles the app.
- `index.js`: The JavaScript file that handles the logic for fetching and displaying weather data.
- `images/`: A directory containing images for different weather conditions (e.g., clear.png, rain.png, snow.png, cloud.png, mist.png).

**How It Works:**
1. The user enters their location in the search bar and clicks the search button.
2. The app makes a request to the OpenWeatherMap API with the entered location.
3. The API responds with weather data, which is then parsed and displayed on the screen.
4. If the location is invalid, an error message is shown.

**Usage:**
1. Open the `index.html` file in a web browser.
2. Enter a city name in the search bar.
3. Click the search button to retrieve and view the weather information.

This Weather App is a great example of how to integrate third-party APIs into a web project and dynamically update the user interface based on the data received. It provides a practical use case for combining HTML, CSS, and JavaScript to create a functional and visually appealing web application.
