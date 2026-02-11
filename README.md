🌤 Weather App (Python)

A simple Python weather application that fetches real-time weather data using the OpenWeatherMap API.

📌 Features

- Get current weather by city name
- Displays:
  - Weather condition
  - Temperature
- Handles invalid city input

🛠 Technologies Used

- Python
- Requests library
- OpenWeatherMap API

📂 Project Structure

weather-app/
│── app.py
│── README.md

⚙️ Installation

1. Clone the repository:

   git clone https://github.com/yourusername/your-repo-name.git

2. Navigate into the project folder:

   cd your-repo-name

3. Install dependencies:

   pip install requests

🔑 Setup API Key

1. Go to https://openweathermap.org/
2. Create a free account
3. Generate your API key
4. Replace this line in app.py:

   api_key = "YOUR_API_KEY"

▶️ Run the Application

   python app.py

Then enter a city name.

Example:

Enter City: London

The Weather in London is: Clouds  
The temperature in London is: 72

⚠️ Note

- Make sure you have internet connection.
- Do not upload your real API key to public repositories.

📜 License

This project is for educational purposes.
