# WeatherDjangoHub

Welcome to the WeatherDjangoHub project! This application is designed to provide real-time weather information for various locations using the Django web framework. The project utilizes weather APIs to fetch current weather data and displays it in a user-friendly interface.

## Features

- **Real-time Weather Data**: Fetches and displays the current weather conditions for any location.
- **Search Functionality**: Allows users to search for weather information by city name.
- **API Integration**: Uses a reliable weather API to gather weather data.
- **Responsive Design**: Mobile-friendly and responsive user interface.
- **Django Backend**: Powered by Django, a high-level Python web framework.

## Installation

To get a local copy up and running, follow these steps:

### Prerequisites

- Python 3.x
- pip (Python package installer)
- Django
- Requests (for API calls)

### Steps

1. **Clone the repository:**
   ```sh
   git clone https://github.com/alihassanml/WeatherDjangoHub.git
   cd WeatherDjangoHub
   ```

2. **Create a virtual environment:**
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install dependencies:**
   ```sh
   pip install -r requirements.txt
   ```

4. **Apply migrations:**
   ```sh
   python manage.py migrate
   ```

5. **Run the server:**
   ```sh
   python manage.py runserver
   ```

6. **Access the application:**
   Open your web browser and go to `http://127.0.0.1:8000`.

## Usage

- **Search for Weather**: Enter the name of the city you want to get the weather information for and click the search button.
- **View Weather Details**: The application will display the current weather conditions including temperature, humidity, wind speed, and more.

## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Contact

Ali Hassan - [@yourtwitterhandle](https://twitter.com/alihassanml) - your-email@example.com

Project Link: [https://github.com/alihassanml/WeatherDjangoHub](https://github.com/alihassanml/WeatherDjangoHub)

---

Feel free to explore the repository, raise issues, and submit pull requests. Thank you for visiting and happy coding!
