# Weather App

## Description
This Python script, along with associated HTML and CSS files, creates a simple web application that allows users to check the weather for a specific city using the OpenWeatherMap API.

## Getting Started
To run the Weather App, follow these steps:

1. Clone this repository to your local machine.
2. Make sure you have Python and Flask installed.
3. Create a `.env` file in the project root directory to store your OpenWeatherMap API key. 
4. Run the `weatherapp.py` script using the command: `python weatherapp.py`
5. Open a web browser and navigate to `http://localhost:5000` to use the app.

## Usage
- Enter the name of a city in the input field and click "Get Weather."
- The app will display the weather information for the entered city, including description, temperature, and humidity.
- If there's an error fetching weather data (e.g., due to an incorrect city name), an error message will be shown.

## File Structure
- `weatherapp.py`: The main Python script that runs the Flask web application.
- `index.html`: The HTML template for the app's homepage, where users can enter a city name.
- `weather.html`: The HTML template for displaying weather information.
- `error.html`: The HTML template for displaying error messages.
- `static/css/styles.css`: The CSS file for styling the web pages.

## Dependencies
- Python
- Flask
- Requests library
- OpenWeatherMap API

## Author
Madeline Martin-Bird
## License
This project is licensed under the [MIT License](LICENSE).
