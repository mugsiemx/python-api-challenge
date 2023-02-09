# python-api-challenge

Module 6 Challenge

WeatherPY

Data's true power is its ability to definitively answer questions. This project takes what we've learned about Python requests, APIs, and JSON traversals to answer a fundamental question: "What is the weather like as we approach the equator?"

Now, we know what you may be thinking: “That’s obvious. It gets hotter.” But, if pressed for more information, how would you prove that? This project dives into the possible relationships with latitude vs maximum temperatures, humidity, cloudiness, and wind speed for a randmomly generated sample of cities. Linear regression modeling is used to describle relationships as a whole and with northern and southern hemispheres in order to search out a correlation.

This project shows different ways to code the charts along with a loop to create all four charts for each hemisphere before the relationship descriptions are listed. The slope intercept is coded to overlay all the charts but does not view on all of them due to the need to change the x,y coordinates.

VacationPY

This project uses our weather data skills to plan future vacations. Also, we use Jupyter notebooks, the geoViews Python library, and the Geoapify API. The main tasks will be to use the Geoapify API and the geoViews Python library and employ your Python skills to create map visualizations.

The first map is created with data from our WeatherPy project which selected a random sampling of cities. With this sample for every city in the city_data_df DataFrame, a map was plotted utilizing amount of humidity to create the size of the point plotted for the city.

A DataFrame of cities with ideal weather conditions is generated. The ideal weather conditions are a maximum temperature betweeen 70°F and 80°F, wind conditions leass than 10 mph and zero cloudiness. Planning a vacation always involves accomodations so we take a list of these great weather places to go to and find hotels within a 10,000 meter radius and plot them on a map. These points contain extra information upon hovering over them.
