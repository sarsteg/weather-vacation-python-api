## Using APIs with Python

This project involved utilizing Python to interact with APIs for data collection and manipulation, with a particular emphasis on visualizing weather data.

The assignment aimed to answer the question, *"What is the weather like as we approach the equator?"* by leveraging Python's capabilities in handling requests, APIs, and JSON data.

### Part 1: WeatherPy

For this section, I created a Python script named `WeatherPy.ipynb`. I utilized the `citipy` library, the OpenWeatherMap API, and my Python skills to analyze weather data from over 500 cities at varying distances from the equator.

**Key features included:**
- Generating random geographic coordinates and finding the nearest city to each coordinate.
- Retrieving weather data from the OpenWeatherMap API for these cities.
- Creating scatter plots to visualize relationships between weather variables and latitude, including temperature, humidity, cloudiness, and wind speed.
- Computing linear regression for each relationship and separating plots into Northern and Southern Hemispheres.

### Part 2: VacationPy

In this section, I planned future vacations based on weather data collected in Part 1. I used Jupyter notebooks, the GeoViews Python library, and the Geoapify API to create map visualizations.

**Key features included:**
- Displaying a point for every city in the DataFrame, with point size indicating humidity.
- Filtering cities based on desired weather conditions (e.g., temperature, wind speed, cloudiness).
- Using the Geoapify API to find nearby hotels for each city.
- Adding hotel names and countries as additional information in the hover message for each city on the map.

The assignment encouraged critical thinking and offered hints and considerations for optimizing the code, such as understanding API usage, testing libraries, and addressing bias in city selection. Overall, completing this task demonstrated a strong understanding of data analytics foundations and provided valuable hands-on experience with Python, APIs, and data visualization.
