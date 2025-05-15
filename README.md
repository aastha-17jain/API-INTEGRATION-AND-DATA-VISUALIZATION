# API-INTEGRATION-AND-DATA-VISUALIZATION

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: AASTHA JAIN

*INTERN ID*:CT06DL932

*DOMAIN*:PYTHON

*DURATION*:6 WEEKS

*MENTOR*:NEELA SANTOSH

This task involves developing a Python-based script that fetches real-time weather data from a public API—specifically, the OpenWeatherMap API—and visualizes the retrieved data using the matplotlib library. The objective is to demonstrate how Python can be used for data acquisition from online services and how such data can be transformed into meaningful visual insights through interactive and informative charts.

The core functionality is divided into three main parts: data fetching, data processing, and data visualization.

1. Fetching Weather Data from a Public API
The script begins by retrieving weather information for a specific city using the OpenWeatherMap API. OpenWeatherMap offers a variety of weather-related data, such as current weather conditions, hourly forecasts, and long-term forecasts. For this task, we utilize the Current Weather Data API, which returns real-time information about a city’s weather, including temperature, humidity, atmospheric pressure, and wind speed.

To access this data, the script uses the requests library in Python to send an HTTP GET request to the API endpoint. The request includes parameters such as the city name and a valid API key. The response is in JSON format, which contains structured weather data fields. Basic error handling is implemented to ensure the request was successful and that the data is correctly returned.

2. Processing the Data
After retrieving the JSON response from the API, the script extracts specific fields of interest. These include:

Temperature (in Celsius)

Feels Like Temperature

Humidity

Pressure

Wind Speed

Weather Condition (e.g., Clouds, Rain)

These metrics are then stored in variables to be used for plotting. This processing step ensures the raw data is cleanly separated into meaningful variables, making the visualization step more manageable.

Additionally, a timestamp is extracted and formatted to display when the data was last updated, adding context to the visualization.

3. Creating a Visualization Dashboard using Matplotlib
The final step involves creating a bar chart to visualize the current weather metrics using matplotlib. Each weather metric is represented as a bar, allowing for easy comparison between variables. The chart includes:

Labels for each weather parameter

Values shown above each bar

A title that displays the city name and weather condition (e.g., "Clouds: Scattered Clouds")

A timestamp showing when the data was last updated

This kind of visualization is not only informative but also aesthetically pleasing, making it easier for users to quickly interpret weather conditions at a glance.

Applications and Benefits
This task is an excellent example of how to combine API integration, data parsing, and data visualization in a Python project. It demonstrates the ability to automate data collection from online services and present it in a user-friendly format. Such skills are essential in data science, software development, and real-world applications like building dashboards, creating weather apps, or monitoring environmental conditions.

Additionally, this project can be extended in numerous ways—such as adding forecast data, integrating with interactive plotting libraries like Plotly or Dash, or building a web app using frameworks like Flask or Streamlit.

![Image](https://github.com/user-attachments/assets/62d1fd38-c133-431b-9f13-e5ff43b730aa)
