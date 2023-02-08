# Weather-Forecasting

In this project, we are going to discuss how to create a weather forecastingapp using tkinter. The GUI app will tell us the current weather of a particular city along with temperature details along with other details.

Modules required: Tkinter: It is a built-in python library for making GUI using tkinter toolkit. Requests: It is a library which helps in fetching the data with the help of URL. It can be installed using the below command:

Weather api Application Programming Interfaces that provide access to current & historical weather data on a global scale. There are several public weather APIs like OpenWeatherMap API, Dark Sky API, & Visual Crossing Weather API. These REST APIs can be used to build powerful weather apps

We can find weather reports such as temperature, humidity, pressure, wind speed and description etc. of any place in the world. You need to provide the name of a place. Not only this you will also get current time of that place.

Also you will get 8 day weather forecast result for your searched name. It is desigend in such way that you are able to find weather report of complete week (7 upcoming days ).

CODE EXPLAINATION:

it will take input(city name) from user and convert it to longitude and latitude
it will convert longitude and latitude to time zone and clock.
now we will use longitude and latitude in api link to get data from OpenweatherApi .
you can import data like, temperature , climate, wind speed, pressure, cloud, image, humidity and many other things you want.
we have use datetime module to get day name .
Technologies used: Python and Python Tkinter GUI Code Editor: Visual Studio Code
