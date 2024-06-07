**Weather App**

### Overview

This Weather App is a simple web application built with React that allows users to check current weather details and a 5-day forecast for a selected city. The application integrates with the OpenWeatherMap API to retrieve real-time weather data.

### Prerequisites

Before running the Weather App, ensure that you have the following installed:

- Node.js
- npm (Node Package Manager)

### Getting Started

1. Clone the repository to your local machine:
2. Navigate to the project directory:
3. Install dependencies:

   ```bash
   npm install
   ```

4. Obtain an API key from OpenWeatherMap:

   - Create an account on [OpenWeatherMap](https://openweathermap.org/).
   - Generate an API key from your account.

5. Configure the API key:

   - Navigate to the `src/api/OpenWeatherService.js` file.
   - Replace `WEATHER_API_KEY` with your OpenWeatherMap API key.

6. Run the application:

   ```bash
   npm start
   ```

   The application will be accessible at `http://localhost:3000` in your web browser.

### Features

1. **Current Weather Details:**
   - Enter a city name to view the current weather details, including:
     - Current temperature
     - Humidity
     - Wind speed 
     - Description of the weather
     - Appropriate icon reflecting the current weather

2. **5-Day Forecast:**
   - View a 5-day forecast for the selected city, displaying:
     - Day
     - Average temperature
     - Description of the weather
     - Appropriate weather icon

3. **Temperature Units:**
   - Toggle between Celsius and Fahrenheit units for temperature measurements.

### Usage

1. Enter a city name in the provided input field.
2. Click the "Search" button to view the current weather details and 5-day forecast.
3. Use the toggle button to switch between Celsius and Fahrenheit units.

