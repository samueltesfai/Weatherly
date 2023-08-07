# Weatherly

Weatherly is a responsive React application that provides users with real-time weather information, forecast, air quality, sunlight details, wind map, and more. It fetches data from an HTTP API and displays the information in various components for an interactive and visually appealing user experience.

The aim of this project is purely educational, serving as a hands-on experience to explore and apply various web development technologies and concepts, fostering learning and growth in the field of software development.

[Click here to view website](https://samueltesfai.github.io/Weatherly)

## Features

### Various Weather Details
Displays the current weather conditions, predicted forecasts, other miscellaneous climate information. 

### Weather Map
An interactive map that displays a live animation showing the wind pattern.

### AI Generated Descriptions
A description using OpenAI's LLM to provide general year-round climate information for specific locations users search.

## Technologies Used

- React.js
- react-router-dom
- AWS Lambda & API Gateway
- OpenAI
- Weatherbit
- Maptiler

## To Do

### Fixing Map Bug
There is a known bug with the Wind Map feature where the map is not rendering properly in the deployed version, although it works locally. A detailed investigation is required to identify and fix the issue. A visual example of what the map should look like is provided below:

<img width="1273" alt="Screen Shot 2023-07-31 at 3 42 43 PM" src="https://github.com/samueltesfai/Weatherly/assets/67299283/d5ff9882-49ef-404c-800a-200ae57aa280">

### Adding Different Types of Weather Maps
Currently, the application only offers a wind map. Future improvements could include adding different types of weather maps to enhance the user experience. Possible additions might include:

- **Temperature Map**: Displaying variations in temperature across different regions.
- **Precipitation Map**: Showcasing rainfall and snowfall patterns.

These enhancements would make the app more comprehensive and engaging for users interested in different weather phenomena.