# Weather-Tracker

Weather-Tracker is a lightweight desktop application that provides real-time weather updates using the OpenWeather API. The app supports current weather data, hourly forecasts, and a 5-day forecast.

![weather-app](https://github.com/user-attachments/assets/3764c02e-53c4-4abd-b359-36a7022c8b8c)

### Windows Installer

Download the latest version from the Releases page

    - Weather-Tracker Setup.exe (Recommended)
    - Weather-Tracker-portable.exe (No installation required).

### System Requirements

    - Windows 10 / 11
    - Internet connection (for weather data retrieval)

## Features

- Search for any city’s weather  
- Current weather conditions (Temperature, Humidity, Wind Speed)  
- Hourly Forecast Graph (12-hour trend)  
- 5-Day Weather Forecast

## Usage

    - Open the app (After installation, find it in the Start menu or Desktop).
    - Enter a city name in the search bar.
    - Click "Get Weather" to fetch weather data.
    
    View:
        - Current Weather Data
        - Hourly Temperature Graph
        - 5-Day Forecast with Weather Icons

## Tech Stack & Dependencies

### Programming Languages & Frameworks

    - Electron.js (for building the desktop app)
    - HTML, CSS, JavaScript (Frontend UI)
    - Chart.js (for graphical weather data)
    - TailwindCSS (for styling)

### Software Dependencies

Dependency        | Purpose  
-----------------|---------------------------------------------  
electron         | Builds the desktop app  
electron-builder | Creates Windows installer  
electron-packager| Packages the .exe files  
node-fetch       | Fetches weather data from OpenWeather API  

## Packaging & Deployment

    - Installer Built With: electron-builder
    - Portable Version: Built using electron-packager
    
## Example Screenshot
![Example](https://github.com/user-attachments/assets/7b5130d2-e7ba-446d-8b5f-71739a2c3399)
    
