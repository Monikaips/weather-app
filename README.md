**Weather App**

**Overview**
This is a simple weather application that fetches and displays the current weather for a specified city using the OpenWeatherMap API. The application allows users to search for weather information by entering a city name in the search bar. The background image dynamically changes based on the weather condition.
--
**Features**
Fetches current weather data using the OpenWeatherMap API.
Displays weather details including temperature, weather description, humidity, and wind speed.
Dynamic background images based on weather conditions.
Responsive design suitable for desktop and mobile devices.
--
**Technologies Used**
1.HTML
2.CSS
3.JavaScript
--
**Prerequisites**
To run this project, you need a basic understanding of web development and an API key from OpenWeatherMap.
--
**Installation**

**Clone the repository:**

git clone https://github.com/Monikaips/weather-app.git
cd weather-app
**Get an API Key:**

Sign up on OpenWeatherMap to get your free API key.
**Configure the API Key:**

Open script.js and replace the placeholder API key with your actual API key:
let weather = {
  apikey: "YOUR_API_KEY_HERE",
  // rest of the code...
};
**Ensure Images are Available:**

Make sure you have the images for different weather conditions in the images folder. The images should match the keys specified in the customBackgrounds object in the script.js file.
--
**Usage**
1.Open the index.html file in your web browser:
   Simply open the index.html file in any web browser to see the app in action.

2.Search for a City:

   Enter a city name in the search bar and either press the Enter key or click the search button.
   The weather details for the specified city will be displayed, and the background image will update based on the current weather conditions.
   
--
**Code Explanation**
*HTML*
The HTML file contains the structure of the app, including the search bar, button, and sections for displaying weather information.

*CSS*
The CSS file styles the app, providing a modern and responsive design. Key styles include:

1.Gradient Background: Provides a visually appealing background.
2.Responsive Design: Ensures the app looks good on both desktop and mobile devices.
3.Dynamic Weather Icons: Displays weather icons dynamically based on fetched data.
*JavaScript*
The JavaScript file handles the following:

1.Fetching Weather Data: Uses the OpenWeatherMap API to get current weather data.
2.Displaying Weather Data: Updates the HTML with weather details and changes the background image based on the weather condition.
3.Event Listeners: Listens for user interactions with the search bar and button to trigger the weather fetch.
--
**Detailed Code Explanation**
The JavaScript file includes detailed comments explaining the functionality of each section.

--
Acknowledgements
OpenWeatherMap for providing the weather data API.
Unsplash and other sources for the background images used in the application.
--
Contact
If you have any questions or suggestions, feel free to open an issue or submit a pull request.
--
