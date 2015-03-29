# sf_crime_map
playing with D3, react, and SF crime data

Took data from https://data.sfgov.org/Geographic-Locations-and-Boundaries/Neighborhoods/ejmn-jyk6? and ran it through
gdal (ogr2ogr -f GeoJSON -t_srs crs:84 foo.geojson foo.shp).

Plan
----
1. Move JS out of index.html and start reasonable structure.
2. Create a module to get the crime data from sfgov and plot it given fixed parameters.
3. Move this under react.
4. Add ability to parametrize scale and date range to look at.
5. Add some filters/display for types of crime.
