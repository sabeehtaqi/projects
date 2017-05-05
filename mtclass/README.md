# Maryland county

Interactive chloropleth map based on data from census.gov

The Goal is to identify the counties with the greatest population.
The chart will show how the population is distributed by age cohorts, which
will tell the story as to what age cohorts are concentrated in specific Counties, e.g., PG County has the largest population ages 20-24, perhaps because of UMD, and Montgomery County seems to attract retirees.

### Data

Project repository: https://github.com/MTClass/Project

Data are from census.gov, both the decennial census and American Fact Finder.

### Instructional demos

Using the [Class-23 demo](https://umbcvis.github.io/classes/class-12) as a starting point,
this demo shows how to reconstruct all the counties from the census tracts.

* https://umbcvis.github.io/projects/mtclass

Starting from [this gist](https://gist.github.com/MTClass/65b5751166dbf5a32a70bf47e41e4a00), the following demo shows how to display the county FIPS when dragging the big yellow ball over the map. This should help answer the question posed in the forum on 5 May.

* https://umbcvis.github.io/projects/mtclass

## To Do

#### Technical

Specific objectives (create a separate gist for each one)

1. Create a population density map with census tract data with the legend
    * http://blockbuilder.org/MTClass/237b48e16999f07a69fa01f880fb02bf
2. On the same map, draw County boundaries in a different color.
3. Create a circle over Rockville that can be dragged on the map
4. Create a hover function so that the counties are colored and the label with the name of the County shows with the arrow motion

#### Documentation

* Add specific links in your repository to identify your data sources -- "census.gov" isn't suffficient.
