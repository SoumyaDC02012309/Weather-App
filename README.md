# Weather Application

This Weather Application provides detailed weather reports for any city, utilizing data from AccuWeather and enhanced with AI-generated insights. It includes graphical forecasts, downloadable CSV tables, and a city map display powered by Streamlit. To use all features, you'll need API keys for Gemini and AccuWeather.

## Features

- **Current Weather Data:**
  - Current Temperature
  - Min and Max Temperature
  - Feels Like Temperature
  - Wind Speed and Direction
  - UV Index

- **AI-Generated Insights:**
  - Pros and Cons related to the current weather conditions.

- **Graphical Forecast:**
  - Plot of Min and Max Temperature forecast for the next 5 days.

- **Downloadable Data:**
  - Weather data in CSV format for detailed analysis.

- **City Map:**
  - Interactive map visualization of the city using **Streamlit** features.

## Getting Started

To run the Weather Application, you need to set up API keys for Gemini and AccuWeather.

### Prerequisites

1. **Obtain API Keys:**
   - Sign up for API keys from:
     - [AccuWeather API](https://developer.accuweather.com/)
     - [Gemini API](https://www.gemini.com/api/docs/)

2. **Installation:**
   - Clone this repository:
     ```bash
     git clone https://github.com/your-username/weather-application.git
     cd weather-application
     ```
   - Install dependencies from `requirements.txt`:
     ```bash
     pip install -r requirements.txt
     ```

3. **Set up API keys:**
   - Add your API keys in the appropriate configuration file or environment variables as per the application's instructions.

### Running the Application

1. Launch the Streamlit app:
   ```bash
   streamlit run Weather App.py
   ```
2. Open the displayed URL in your browser to access the application.

## Application Walkthrough

1. Enter the name of the city in the search bar.
2. View detailed weather information, including:
   - Current temperature, UV Index, and wind conditions.
   - AI-generated pros and cons of the weather.
3. Explore the interactive map of the city.
4. View the 5-day forecast in a graphical format.
5. Download the weather data as a CSV file for further use.

## APIs Used

- [AccuWeather API](https://developer.accuweather.com/)
- [Gemini API](https://www.gemini.com/api/docs/)

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a feature branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-name`).
5. Open a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements

- Weather data powered by **AccuWeather**.
- AI insights powered by **Gemini**.
- Interactive map powered by **Streamlit Folium**.
