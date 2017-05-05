## Anacostia Watershed

Purpose/Goals: Create interactive webmap of census demographic data in the Anacostia Watershed

### Data

Project repository: https://github.com/leenoah1/class_project

**Data sources**

* Link to Anacostia Watershed data from MWCOG (current employed organization. Data used to clip to census.gov tract data): http://www.anacostia.net/maps/Data_download.html
* Maryland census tract data from census.gov: https://www.census.gov/cgi-bin/geo/shapefiles/index.php?year=2010&layergroup=Census+Tracts

**Brief Description of Geoprocessing:**

* clipped Anacostia watershed shapefile to census.gov Maryland tract shapefile
* recalculated population demographics of new tracts that were clipped by the watershed shapefile
* calculated new geometry (acres)
* calculated new population numbers based on new tract geometry/area

## To Do

These are next steps for the project.

#### Documentation

Add the following content to the README.md in your repo.

1. 1 or 2 sentences describing overall project goals, e.g., interactive tool?, hypothesis test? (50% complete)
2. Attribution and links to all data sources (20% complete)
    * describe parameters used in census.gov API query
    * need source of watershed data
3. Extremely brief description of all pre-processing (0% complete)
    * For example: Converted census.gov shapefile to GeoJSON using an online tool (?? -- add link to tool)
    * Clipped to watershed with GIS tools (?? -- which tools)

#### Technical

For each steps, create a separate gist/block -- link to these in your repo's README.md

1. Plot GeoJSON -- put it in a gist and link to it from your repo's README.md
2. Plot GeoJSON on top of the slippy map (zoomable map tiles) from the Class 12 demo
3. Add interaction using data in the GeoJSON file

If all goes well with these steps, consider using Leaflet...

*  leaflet gist: https://gist.github.com/leenoah1/c6cb58257f6069bfb9d1d305df36e621

