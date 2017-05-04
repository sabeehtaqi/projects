## Population-chloropleth time series

Goal: A Chloropeth map of population estimates for the counties in USA from the year 2010 to 2016. and try to make it interactive by a scroll bar or something similar.

### Data

https://github.com/sabeehtaqi/FINAL-PROJECT/blob/master/PopulationEstimatesProject%20Final.csv
From 
https://www.census.gov/data/tables/2016/demo/popest/nation-total.html

## To Do

Next steps for the project....

#### Documentation

##### Add links to all data sources

Data were downloaded in excel format. Several columns were not useful so the data were refined and converted to CSV

#### Technical

For each steps, create a separate gist/block -- link to these in your repo's README.md

1. Plot Topo/GeoJSON for region of interest.
    * Template block from Mick Bostock -- https://bl.ocks.org/mbostock/4060606
2. Integrate census data
    * Will need to adapt the template to CSV data
    * The template block loads population data (CSV) using d3map()
    * Identify in detail what is going on with d3.map in the example
    * Create a simple example (start by using something that can be manipulated in console)
3. Add interaction somehow (TBD)
