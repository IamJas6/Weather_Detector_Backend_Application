# Weather_Detector_Backend_Application

---

## Overview

This is a backend application developed using Python and Django framework. The purpose of this application is to display weather information such as country code, coordinates, temperature, pressure, and humidity for a given city or location. The weather data is retrieved using the OpenWeather API.

## Getting Started

### Prerequisites

Before running the application, make sure you have the following installed on your system:

- Python (version 3.x)
- Django framework
- Requests library (to make HTTP requests)

### Installation

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/your-username/weather-detector.git
   ```

2. Navigate to the project directory:

   ```bash
   cd weather-detector
   ```

3. Install the required Python packages:

   ```bash
   pip install -r requirements.txt
   ```

### Configuration

1. Obtain an API key from OpenWeather by signing up at [OpenWeather API](https://openweathermap.org/).

## Usage

To run the application, use the following command:

```bash
python manage.py runserver
```

Once the server is running, open a web browser and go to `http://localhost:8000/` to access the application.

### Searching for Weather Data

1. In the search bar, enter the name of a city or location.
2. Press the "Search" button.
3. The application will display the weather information for the specified location, including the country code, coordinates, temperature, pressure, and humidity.

## License

This project is licensed under the [License](Apache.LICENSE.2.0).

---
