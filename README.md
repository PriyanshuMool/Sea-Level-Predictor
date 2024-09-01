### SEA LEVEL PREDICTOR

Analyzed the global average sea level changes dataset from 1880 and used it to forecast sea level changes through 2050.

Steps completed:

* Imported the data from "epa-sea-level.csv" using Pandas.
* Created a scatter plot with matplotlib, using "Year" on the x-axis and "CSIRO Adjusted Sea Level" on the y-axis.
* Used the "linregress" function from "scipy.stats" to calculate the slope and y-intercept for the line of best fit, then plotted this line over the scatter plot, extending it to the year 2050 to estimate future sea level rise.
* Created another line of best fit using only data from 2000 onward, and extended this line to 2050 to predict future sea level rise based on recent trends.
* The graph is labeled with "Year" on the x-axis, "Sea Level (inches)" on the y-axis, and titled "Rise in Sea Level."
* Unit tests are included in "test_module.py".


### Testing
The tests from "test_module.py" have been imported into "main.py" for ease of use. They will automatically run when you click "run."

### Data Source
Global Average Absolute Sea Level Change, 1880-2014, provided by the US Environmental Protection Agency, using data from CSIRO (2015) and NOAA (2015). The dataset is accessible at CSIRO, 2015; NOAA, 2015.
https://datahub.io/core/sea-level-rise
