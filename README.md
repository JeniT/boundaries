This repo is for me to experiment with support for GeoJSON and TopoJSON in GitHub using boundary files.

## What I Done

 1. install gdal with `$ brew install gdal`
 2. install topojson with `$ npm install -g topojson`
 3. map the downloaded Shape files to using lat/long coordinates with `$ ogr2ogr -t_srs WGR84 <input> <output>`
 4. map the Shape files to topojson using `$ topojson -q <quality> -o <output> <input>`