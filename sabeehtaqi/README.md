## Project title

Chloropeth Map of Population estimate for Counties in USA

### Data

https://github.com/sabeehtaqi/FINAL-PROJECT

## To Do

Merge the data in CSV format with the counties

#### Documentation

Add the following content to the README.md in your repo.

1. 1 or 2 sentences describing overall project goals, e.g., interactive tool?, hypothesis test? (0% complete)

My Project Goal is to make a Chloropeth map of Population estimates for the counties in USA from the year 2010 to 2016 and try to make it interactive by a scroll bar or something similar.

2. Attribution and links to all data sources (0% complete)
 
 Census Data 2010
 Population Estimates County data All States

3. Extremely brief description of all pre-processing (0% complete)

Data was in excel format with a number of columns that were not useful so I refined the data and convert it to CSV

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

