# Weather Information Visualization App

A web application that fetches and displays real-time weather information using ES6 features and OpenWeatherMap API.

## Features
- Real-time weather data fetching using OpenWeatherMap API
- Interactive UI with temperature and humidity visualization
- Error handling and user-friendly interface
- Modern ES6+ JavaScript features implementation

## Prerequisites
- Modern web browser (Chrome, Firefox, Safari, or Edge)
- Internet connection
- OpenWeatherMap API key

## Getting Started

### Step 1: Get API Key
1. Visit [OpenWeatherMap](https://openweathermap.org/) and sign up for a free account
2. Get your API key from the dashboard
3. Open `script.js` and replace `YOUR_API_KEY` with your actual API key:
   ```javascript
   const apiKey = 'YOUR_API_KEY';
   ```

### Step 2: Running the Application
1. Open your terminal and navigate to the project directory:
   ```bash
   cd "c:\Users\rhima\OneDrive\Desktop\sdc lab experiments\Skill-Development-Lab\Experiment-04_Weather_information_Visualization_ES6\Weather-info-app"
   ```

2. Start a local server using Python (recommended for proper CORS handling):
   ```bash
   python -m http.server 8000
   ```

3. Open your web browser and go to:
   ```
   http://localhost:8000
   ```

### Step 3: Using the Application
1. Enter a city name in the input field
2. Click the "Fetch Weather" button
3. The application will display:
   - Current temperature
   - Humidity percentage
   - Weather description
   - Interactive bar chart showing temperature and humidity

## Technologies Used
- HTML5
- CSS3
- JavaScript (ES6+)
- Chart.js
- OpenWeatherMap API

## ES6 Features Implemented
- Arrow Functions
- Promises
- Async/Await
- Template Literals
- Destructuring
- Default Parameters

## Troubleshooting
- If you encounter CORS errors, make sure you're running the application through a local server
- If the API call fails, verify that your API key is correctly configured
- Check the browser's developer console (F12) for any error messages

## Author
M Swayam Prakash

## License
This project is licensed under the MIT License.