# Weather App

This is a basic web application that provides weather conditions and temperature details for any city in the world.

## Features

- Search for the current weather of any city.
- Displays temperature, weather status, and "feels like" temperature.
- Handles invalid city names gracefully with a user-friendly error page.

## Tech Stack

- **Backend**: Python with Flask
- **Frontend**: HTML, CSS (responsive design)
- **API**: [OpenWeatherMap API](https://openweathermap.org/)
- **Web Server**: Waitress (for production)

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone <repository-url>
2. Create a virtual environment and activate it:
    ```bash
    python -m venv .venv
    .venv\Scripts\activate  # On Windows
    source .venv/bin/activate  # On macOS/Linux
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
4. Create a .env file in the root directory and add your OpenWeatherMap API key:
    ```bash
    API_KEY=your_openweathermap_api_key
5. Run the application:
    ```bash
    python [server.py](http://_vscodecontentref_/1)
6. Open your browser and navigate to:
    ```bash
    http://localhost:8000