# geospatial
Code highlighting various geospatial processes.

The repo is divided into 3 major sections: 
- Data (Data Sourcing, Data Ingestion, Data Transformation, and Data Loading)
- Geoprocessing (Setting CRS, fixing geometry and topology issues. Perform spatial analysis.)
- Visualization (Mapping and cartography)

## Data
### Data Sourcing
#### US Census Bureau Places Cartographic Boundaries
Example data will be made available by way of the US Census Bureau's Place level Cartographic Boundary data.<br/>Download URL: https://www2.census.gov/geo/tiger/

This data is a polygon geometry which represents US Census designated Places.  For this use case, the latest version of the data is acceptable.

#### Global Wildfire Hotspot Locations - NASA
Fire hotspot data will also be accessed from NASA | LANCE | FIRMS.<br/>Download URL: https://firms.modaps.eosdis.nasa.gov/map/

This data is a point geometry representing locations where fire was detected by satellite.  For this use case, we will use data for the past year.

### Data Ingestion
Install ``````geopandas`````` library to read in files.
Further dependencies include ``````pandas fiona shapely pyproj fastkml matplotlib contextily``````
### Data Transformation
### Data Loading

## Geoprocessing
### geopandas library
