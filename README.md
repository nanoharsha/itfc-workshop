# Data and Maps workshop
#### [IT for Change](http://itforchange.net), December 18-20 2013, Bangalore.
---

1. Geodata basics and management
  0. [What Maps are Made of?](https://github.com/veltman/learninglunches/tree/master/maps#what-maps-are-made-of)
    * Datum, projection, geometry.
    * Map Tiles. 
  1. [Formats](http://geohackers.in/2013/11/spatial-data-formats-101/) - 
    1. CSV
    2. JSON
    3. GPX
    4. KML
    3. Shapefile
    3. GeoJSON
    6. OSM XML
      * Tags
    7. TopoJSON
    8. SVG
  2. [Sources](http://datahub.io/group/geodata)
    1. OpenStreetMap
        1. [Country wide](http://download.geofabrik.de/openstreetmap/)
        2. [Metros](http://metro.teczno.com/)
          * Exercise - load Bangalore data into QGIS.
          * Exercise - and query for specific tags.
    2. [Natural Earth](http://www.naturalearthdata.com/downloads/) 
    3. [GeoNames](http://geonames.org) (Daily data dump and a web service)
    4. [Landsat](http://landsat.gsfc.nasa.gov/) (Landsat data have been used to monitor water quality, glacier recession, sea ice movement, invasive species encroachment, coral reef health, land use change, deforestation rates and population growth.)
    5. [Administrative Areas: GADM](http://www.gadm.org/)
      * Exercise - overlay GADM over OSM data in QGIS.
  3. [Spatial Queries](https://github.com/mikelmaron/Cartonama/blob/master/cartonama.md#spatial-predicates)
  3. Conversion
    1. [GDAL/OGR](https://github.com/mikelmaron/Cartonama/blob/master/cartonama.md#data-swiss-army-knives)
      * Exercise - Convert GADM data to GeoJSON using QGIS and CLI.
    2. [OGRE](http://ogre.adc4gis.com/)
    3. [Kml2Gpx](http://kml2gpx.com/)
  
2. OpenStreetMap
  1. Extraction
    1. [Overpass API](http://wiki.openstreetmap.org/wiki/Overpass_API)
    2. [Overpass Turbo](http://overpass-turbo.eu/)
    3. [Osmosis](https://wiki.openstreetmap.org/wiki/Osmosis), [extraction](https://github.com/mikelmaron/Cartonama/blob/master/cartonama.md#extract-specific-key-value-pairs)

2. [Pandas](https://github.com/geohacker/itfc-workshop/edit/master/README.md) - overview

4. Visualisation - overview and examples.
  0. [QGIS](http://geohackers.in/2013/05/adding-the-spatial-element-to-your-data/#more-73)
    * Exercise - taluk boundary, csv, extract, map.
    * Exercise - make a heatmap.
  1. [Leaflet.js](http://leafletjs.com/examples.html)
    * Exercise - [basic map setup](http://leafletjs.com/examples/quick-start.html)
    * Exercise - [layers](http://leafletjs.com/examples/layers-control.html)
    * Exercise - [GeoJSON](http://leafletjs.com/examples/geojson.html)
    * Exercise - [Clustering](https://github.com/Leaflet/Leaflet.markercluster)
    * Exercise - [Zoom Levels and layers](https://github.com/klpdotorg/klpwww/blob/master/js/maps.js#L227-L255)
  2. [D3.js](http://alignedleft.com/tutorials/d3)
    * TopoJSON - [installation](https://github.com/mbostock/topojson/wiki/Installation), [usage](https://github.com/mbostock/topojson/wiki/Command-Line-Reference#usage)
    * Exercise - make a map from GeoJSON. Also, [see Mike's guide](http://bost.ocks.org/mike/map/)
    * Exercise - add data and make it a [choropleth](http://bl.ocks.org/mbostock/4060606).
    * Learn interaction.
  3. [TileMill](http://dataforradicals.com/the-insanely-illustrated-guide-to-your-first-tile-mill-map/)
    * Exercise - make a choropleth
    * Exercise - Interaction

5. [General UI/UX guidelines](https://www.gov.uk/design-principles)

6. Reading List
  1. [MDN on JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide)
  2. [Git for Grownups](http://24ways.org/2013/git-for-grownups/)
