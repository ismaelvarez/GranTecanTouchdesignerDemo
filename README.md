# GranTecanTouchdesignerDemo

Demo project using the data from a observation night.

I developed a component to read the telescope data from a CSV, and then, using an ExectionDAT node, every frame outputs the values in a table (in a loop).

The input is the path of the CSV file.

At the moment, we have the telescope motion, elevation, azimuth and dome rotation, and a couple of sensors (temperature, humidity, etc) outside the building. 

EMCS/WeatherStation/humidity -> Percentage 
EMCS/WeatherStation/temperature	-> Temperature in Celcius
EMCS/WeatherStation/windSpeed	-> WindSpeed in m/s
MACS/ElevationAxis/position	-> Elevation motion in degrees.
MACS/AzimuthAxis/position	-> Azimuth rotation in degrees.
ECS/DomeRotation/actualPosition -> Dome rotation in degrees.

The component is saved in component folder, DataSimulator.tox, and the CSV file in data.
