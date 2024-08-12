# Weather App

This Python script fetches the current weather conditions for a specified city using the OpenWeatherMap API.

## Features

- Fetches and displays the current weather conditions for a given city.
- Outputs the city name, temperature, weather description, and how it feels like in Celsius.

## Requirements

- Python 3.x
- The following Python packages:
  - `requests`
  - `python-dotenv`

## Installation

1. Clone the repository or download the script.

2. Install the required Python packages:

    ```bash
    pip install requests python-dotenv
    ```

3. Create a `.env` file in the root directory of your project. Add your OpenWeatherMap API key to the `.env` file as follows:

    ```bash
    API_KEY=your_openweathermap_api_key
    ```

4. Run the script:

    ```bash
    python weather_app.py
    ```

## Usage

1. When prompted, enter the name of the city for which you want to retrieve the weather conditions.

2. The script will output the current temperature, weather description, and how it feels like in Celsius for the specified city.


## Notes

- Ensure that your API key is valid and that you have internet access when running the script.
- You can obtain an API key by signing up at [OpenWeatherMap](https://openweathermap.org/).

## License

This project free to use and anyone can recreate.

