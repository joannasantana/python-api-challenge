# Python Api Challenge

Background:

Data's true power is its ability to definitively answer questions. So, let's take what you've learned about Python requests, APIs, and JSON traversals to answer a fundamental question: "What is the weather like as we approach the equator?"

Now, we know what you may be thinking: “That’s obvious. It gets hotter.” But, if pressed for more information, how would you prove that?

Methods:

OpenWeatherMap API was used to retrieve weather data from over 500 cities across the globe. Scatter plots and linear regression was used to compare the relationship between latitude and four weather categories: temperature, humidity, cloudiness, and wind speed.

Then, the list of cities was narrowed down to those representing my own personal ideal weather conditions. Geoapify API was then used to locate hotels in these cities. Hotels were then mapped using hvplot.

Skills demonstrated:
- API calls from OpenWeather and GeoApify
- Looping through and pulling data from JSON results
- Python function creation
- Generation of graphs using pandas and matplotlib
- Regression and corrolation analysis
- Plotting on world maps using hvplot