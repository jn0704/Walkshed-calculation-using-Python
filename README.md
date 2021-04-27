# Walkshed-calculation-using-Python
Through two scripts, we can create walksheds from all linestring features in a pedestrian path layer.
The outputs would be shapefile including walkshed features

## Graph calculation
### Description
This script converts pedestrian path layer into graph
### Preprocessing
The pedestrian path layer must be a shapefile including 'NUM' amd 'LEN_10M' attribute as ID and length of linestring feature
### Requirements
Python 3.x
Gdal
NetworkX

## Walkshed calculation
### Description
This script creates walksheds from all line features of pedestrian path layer
### Preprocessing
This script requires results materials from 'Graph calculation'
### Requirements
Python 3.x
Gdal
NetworkX
