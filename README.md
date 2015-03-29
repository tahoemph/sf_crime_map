# sf_crime_map
playing with D3, react, and SF crime data

Took data from https://data.sfgov.org/Geographic-Locations-and-Boundaries/Neighborhoods/ejmn-jyk6? and ran it through
gdal (ogr2ogr -f GeoJSON -t_srs crs:84 foo.geojson foo.shp).
