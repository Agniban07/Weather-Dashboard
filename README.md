# Weather Dashboard-app
a weather app using html css js and openweather api

# index-html
The HTML file 'index.html' is the backbone of a Weather App project. It establishes the structure and content of the web page, integrating essential elements for user interaction. Through HTML5 markup, it defines the layout, including search functionality, weather details display areas, and placeholders for dynamic content. It sets the stage for a responsive and visually appealing interface, paving the way for a seamless user experience in exploring and retrieving weather information. This HTML file serves as the foundation for combining design and functionality, forming the core structure of the Weather App

# wapp-css
This CSS stylesheet is designed to stylize and enhance the visual presentation of a web page, likely used in conjunction with an HTML file for a Weather App project. Here's an overview of the provided CSS:

Fonts: Imports a Google Font ('Dosis') to be used throughout the page. There seems to be an attempt to use 'Comforter Brush' as well, though it might not be correctly implemented due to specifying two font families in the same declaration.

Body Styling: Configures the body element to use flexbox for layout, centering content both horizontally and vertically. It sets the background image to a random image from Unsplash, providing a dynamic and visually appealing backdrop for the app. It also specifies font families, ensuring a consistent typography style.

Container Styling: Styles the main container holding the weather information. It provides a semi-transparent black background with rounded corners for the weather display, creating a visually appealing card-like appearance.

Search Bar Styling: Defines the appearance of the search bar and search button, employing a consistent color scheme and a circular button design. It also includes hover effects to improve user interaction and feedback.

Detail Section Styling: Establishes the layout for displaying weather details using flexbox, setting margins for spacing.

Temperature Styling: Sets the font size and padding for the temperature display.

SVG Icon Styling: Defines the appearance and size of SVG icons used in the project, with a white fill color and a blue stroke for a specific circle element within the SVG.

# wapp-js
API Integration: The fetchw method within the weather object connects to the OpenWeatherMap API to retrieve weather data based on a provided city name.

Display Functionality: The displayw method in the weather object formats and displays the fetched weather data on the webpage. It extracts specific information like location, weather description, temperature, humidity, and wind speed from the API response and updates designated HTML elements with this data.

Search Functionality: The search method captures user input from a search bar and triggers the fetchw method to retrieve weather information for the specified city.

Event Listeners: Event listeners are attached to both the form submission and button click events. These listeners call the search method when triggered, initiating the weather data retrieval process based on user input.

Rendering Data: Upon successful data retrieval, the JavaScript code dynamically updates specific elements on the webpage, such as displaying the location name, weather icon, weather description, temperature in Celsius, humidity percentage, and wind speed in kilometers per hour.

Overall, this script combines API interaction, data handling, and HTML element manipulation to create a user-friendly weather information display system, allowing users to search for weather details by city name and view real-time updates on a webpage.



