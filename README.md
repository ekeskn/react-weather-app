# Weather App

A simple React application to display current weather and 5-day forecast using the OpenWeatherMap API.

## Features

- Display current weather information for a selected city.
- Show 5-day forecast with temperature, weather icon, and description.
- Choose a city from a list of Turkish provinces.
- Dark mode toggle for better user experience.

## Technologies Used

- **React**: A JavaScript library for building user interfaces.
- **Axios**: A promise-based HTTP client for making requests to the OpenWeatherMap and Turkish cities APIs.
- **Context API**: Used for managing the theme (light/dark mode) globally.

## Getting Started

1. **Clone the repository:**

    ```bash
    git clone https://github.com/your-username/weather-app.git
    ```

2. **Navigate to the project directory:**

    ```bash
    cd weather-app
    ```

3. **Install dependencies:**

    ```bash
    npm install
    ```

4. **Run the application:**

    ```bash
    npm start
    ```

5. Open your browser and go to `http://localhost:3000` to view the app.

## Configuration

Before running the application, obtain an API key from [OpenWeatherMap](https://openweathermap.org/) and replace the `apiKey` variable in the `Weather.js` file.

```javascript
const apiKey = "your_openweathermap_api_key";
