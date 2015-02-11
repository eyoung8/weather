# weather
Script that accesses and prints weather information on a city retrieved from yahoo's weather api. 
On command line specify city (lowercase, no spaces), state (lowercase, abbreviation, eg. ny) to select the location
Display options include: temp condition windchill high low humidity date location
Example call: python weather.py newyork ny temp condition windchill high low humidity date location

Yahoo weather API can be found at:
https://developer.yahoo.com/yql/console/#h=select+*+from+weather.forecast+where+woeid+in+(select+woeid+from+geo.places(1)+where+text%3D'dasdas%2C+asdafaf')
https://developer.yahoo.com/weather/
