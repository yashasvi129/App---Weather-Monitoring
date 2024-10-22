# Weather Data Retrieval and Analysis System

<img width="946" alt="image" src="https://github.com/user-attachments/assets/71e54297-5572-45a5-93e6-a95654cf2959">

Hosted link: https://github.com/yashasvi129/App---Weather-Monitoring.git


## Overview

This project provides a system to fetch weather data from the OpenWeatherMap API at customizable intervals, convert temperature units according to user preferences, and deliver daily weather summaries, including additional metrics like humidity and wind speed. It is designed to be easy to set up, robust, and scalable for future improvements.

## Features

- **System Setup:** Connects to the OpenWeatherMap API using a valid API key.
- **Data Retrieval:** Simulates API calls at configurable intervals to retrieve and parse weather data for specified locations.
- **Temperature Conversion:** Converts temperature values from Kelvin to Celsius or Fahrenheit based on user preference.
- **Daily Weather Summary:** Simulates weather updates over several days and calculates average, maximum, minimum temperatures, and dominant weather conditions.
- **Additional Parameters:** Supports retrieval and analysis of additional weather parameters such as humidity and wind speed.
- **5 days Weather Forecast** 

## Design Choices

- **Modularity:** The system is divided into distinct modules for initialization, data retrieval, temperature conversion, and summary generation, making it easy to maintain and extend.
- **Configurability:** API call intervals and temperature units are configurable to allow flexibility.
- **Extensibility:** Designed to easily incorporate additional weather parameters from the OpenWeatherMap API.

## Requirements
- Screen 1070*680 minimum
- Nodejs (optional in case system do not have live server utility)

## Getting Started

### Prerequisites

- Node.js and npm installed

### Installation

1. **Clone the Repository**
   ```bash
   git clone "https://github.com/Santosh-2003-sahoo/App2-Weather-app.git"
   cd App2-Weather-app
   ```

2. **Install Backend Dependencies**

   ```bash
   npm install
   
   ```
   
3. **run live server

   ```bash
   npm install http-server -g
   http-server -p 8080
   ```

## Running Tests

You can add and run tests to ensure everything is working correctly.
```
created by: yashasvi garg
