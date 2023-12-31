# python-api-challenge
 MSU Data Analytics BootCamp Module 6 Challenge

Code file names: '/WeatherPy/WeatherPy.ipynb' and '/WeatherPy/VacationPy.ipynb'

These Jupyter Notebooks perform the following functions:

The WeatherPy Notebook randomly generates a group of 1500 latitude and longitude combinations, which are then used to search for the nearest city. Each time a city is found near our random coordinates, it is stored in a list. The notebook then performs an API call to the OpenWeather database and pulls the current values for a specific set of weather data (i.e., temperature, humidity, wind speed, and cloudiness) for the randomly selected cities. Scatterplots of latitude vs. the weather data are generated for all four sets of values, along with linear regressions for the latitude vs. weather data broken down by northern and southern hemisphere.

The VacationPy Notebook then takes the list of random cities and displays each city on a map of the world with the size of the circle representing the city proportional to the humidty number pulled from the OpenWeather database. It then filters the city list based on a pre-specified set of weather and geographic parameters, makes a API call to the Geoapify Database, and finds the first hotel witin our filtered list of cities within 10000 meters. The cities in which those hotels are located are displayed on a new map which also shows the name of the hotel and the country in which the city is located when hovered over with the mouse.

*Code sourcing statement*
-----------------------

I did use a natural language description of the desired code's functions entered into ChatGPT 3.5 to help with code syntax. I did copy pieces of that code in order to be more efficient, but I tailored it to fit all of the desired functions of this particular project. I did not directly copy and paste any of this code from the internet otherwise (e.g., from StackExchange or any other webpage). I did not seek any assistance or use code written by my peers or instructors for this challenge.

End of code sourcing statement.

 ----------------------

 The repository also contains the output files generated by the notebook in a directory called 'output_data'.
