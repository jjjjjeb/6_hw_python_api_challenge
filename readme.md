# WeatherPy

Analysis on weather data pulled from open weather map api utilizing python, pandas, matplotlib & citipy.
Jupyter notebook [here](./WeatherPy/WeatherPy.ipynb).
Demo site [here](https://jjjjjeb.github.io/Web_Design_Challenge/).

![Fig](./imgs/Latitude_vs_Temp.png)

### Findings

1. The generated scatter plot on current global temperatures and latitude proved that at any given time cities that are closer to the equator are hotter than cities further away. I used current temperature data, but I think a more accurate (and also free) recording would be to simply pull the max or min temp's rather than the current temperature. Either of the max or min temp's could be used by themselves to chart the graphs or an average of the max and min temperatures. This would account for variations due to day and night.
2. Humidity data points pooled a bit higher (80-100%) in latitudes over 40 degrees but overall data points were dispersed throughout the entire graph. Therefore, I would avoid making any quick connections between humidity and latitude. City's that are land locked vs city's that are near water will affect the humidity as well as temperature.  We don't have data on city nearness to the ocean or large bodies of water. 
3. Latitude was not found to be a good indicator for predicting percentage cloud cover or wind speed.
