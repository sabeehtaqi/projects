## Population-chloropleth time series

Goal: A Chloropeth map of population estimates for the counties in USA from the year 2010 to 2016, with an interactive by a scroll bar or something similar.

### Data

Project repository: https://github.com/sabeehtaqi/FINAL-PROJECT

### Instuctional demo

This demo shows how to read CSV data for the project into a map of counties for the entire US.

*  https://umbcvis.github.io/projects/sabeehtaqi/

## To Do

Next steps for the project....

#### Documentation

##### Add links to all data sources

Data were downloaded in excel format. Several columns were not useful so the data were refined and converted to CSV

#### Technical

Starting with the instructional demo above [Mick Bostock's Chloropleth map](https://bl.ocks.org/mbostock/4060606):

1. Integrate census data
    * Will need to adapt the demos to CSV data
        * Will need to construct 5-digit FIPS ID from the CSV data
    * The template block loads population data (CSV) using d3map()
    * Identify in detail what is going on with d3.map in the example
    * Create a simple example (start by using something that can be manipulated in console)
2. Add interaction somehow (TBD)

Note: For each step, create a separate gist/block -- link to these in your repo's README.md.
