# python-api-challenge
python-api-challenge

	Scope The scope for this activity was to understand the weather pattern in relationship with location in order to find an optimal vacation destination.

Part 1-WeatherPy 
	A python script was created on Jupyter notebook and jupyter lab in order to better visualize the data. The weather of 500+ cities were analyzed based on location (Longitud, Latitud) and its location relative to the ecuador.

The first requirement is to create a series of scatter plots to showcase the following relationships:

Temperature (F) vs. Latitude
	Plot analysis image: the change in temperatures is clearly visible as the location move toward the equator temperatures start to rise but as the move away from the equator, temperatures start to decent once more describing a parabola
Humidity (%) vs. Latitude
	Plot analysis image: the humidity levels change as the location moves from the equator. The closer to the equator the more humid the environment.
Cloudiness (%) vs. Latitude
	Plot analysis image:There seems to be not a clear relationship between the formation of clouds and the geographic location.
Wind Speed (mph) vs. Latitude:
	Plot analysis image: there is a bigger difference between wind speed in the northern hemisphere and the southern hemisphere. Wind speeds are greater in the north than the south but the variation in speed is greater in the southern hemisphere. 

After each plot, add a sentence or two explaining what the code is analyzing.

The second requirement is to run linear regression on each relationship. This time, separate the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude):

Northern Hemisphere - Temperature (F) vs. Latitude
	for this side os the sphere there is a strong negative correlation between latitude and max temperature for northern hemisphere as we move away from the equator.
Southern Hemisphere - Temperature (F) vs. Latitude
	for this side os the sphere there is a strong Positive correlation between latitude and max temperature for northern hemisphere as we move in the equator.
Northern Hemisphere - Humidity (%) vs. Latitude
	There is a moderate positive correlation between latitude and humidity
Southern Hemisphere - Humidity (%) vs. Latitude
There is a moderate positive correlation between latitude and humidity
Northern Hemisphere - Cloudiness (%) vs. Latitude
	There is a weak positive correlation between latitude and cloudiness for southern hemisphere
Southern Hemisphere - Cloudiness (%) vs. Latitude
	There is a strong positive correlation between latitude and cloudiness for southern hemisphere
Northern Hemisphere - Wind Speed (mph) vs. Latitude
	There is a weak positive correlation between latitude and wind speed for southern hemisphere.
Southern Hemisphere - Wind Speed (mph) vs. Latitude
	There is a weak negative correlation between latitude and wind speed for southern hemisphere.

