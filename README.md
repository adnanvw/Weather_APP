# Weather Web Application

Welcome to the Weather Web Application project! This front-end application, built with React, allows users to retrieve current weather information for a specific location using a Weather API. This README provides information on the project's features, installation, usage, and how to contribute.

## Features

- **Search by Location:** Easily search for the current weather in a specific location by entering a city or zip code.

- **Display Weather Data:** Get real-time information on temperature, weather conditions, humidity, wind speed, and a visual weather icon representing the conditions.

## Installation

To run the Weather Web Application on your local machine, follow these steps:

1. Clone the repository to your local machine:
   
   ```bash
   git clone https://github.com/adnanvw/Weather_APP.git
   ```

2. Navigate to the project directory:

   ```bash
   cd weather-app
   ```

3. Install the required dependencies:

   ```bash
   npm install
   ```

4. Create a `.env` file in the project's root directory and add your Weather API key. Sign up for a free API key at [OpenWeatherMap](https://openweathermap.org) and add the following line to your `.env` file:

   ```env
   REACT_APP_API_KEY=your_api_key_here
   ```

5. Start the development server:

   ```bash
   npm start
   ```

6. Open your web browser and go to [http://localhost:3000](http://localhost:3000) to access the Weather Web Application.

## Usage

1. Enter the location (e.g., city name) into the search input field.

2. Click the "Search" button or press "Enter" to retrieve current weather information for the specified location.

3. The weather data will be displayed below the search bar, providing details such as temperature, weather condition, humidity, wind speed, and a weather icon.

4. You can continue searching for different locations by entering new queries in the search bar.

## Dependencies

This project relies on the following dependencies:

- React: A JavaScript library for creating user interfaces.
- Axios: A promise-based HTTP client for making API requests.
- [OpenWeatherMap API](https://openweathermap.org/): The Weather API used to fetch weather data.

## Project Structure

The source code of this project is organized as follows:

- `src/`
  - `components/`: Contains React components.
  - `App.js`: The main application component.
  - `index.js`: The entry point of the application.

## Contributing

We encourage contributions to this project! If you'd like to contribute, please follow these steps:

1. Fork the repository to your GitHub account.

2. Create a new branch with a clear name for your feature or bug fix.

3. Make your changes and commit them with concise and descriptive messages.

4. Push your changes to your forked repository.

5. Create a pull request to the original repository, explaining the changes you made and their significance.

Thank you for using and contributing to the Weather Web Application! Enjoy staying updated on the weather! 🌦️