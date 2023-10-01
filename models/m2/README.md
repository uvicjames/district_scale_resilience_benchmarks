# District-scale Resilience Benchmarks: Model 2

The first model contains an electricity network and a water distribution network that are defined upon a small, artificial block/lot/street layout. There is no terrain file, and all vertices are on the z=0 plane.


# Model Files

The following files are currently included:

| File  | Description |
| ------------- | ------------- |
| _blocks.xml_  | an XML file that contains block and lot geometry  |
| _streets.graphml_| a GraphML file that stores the street network.|
| _water.graphml_|  a GraphML file that stores a water distribution network.|
| _electricity.graphml_| a GraphML file that stores a low-voltage ("LV") electricity network.|
| _interconnects.xml_| an XML file that defines physical dependencies between nodes in the water and electricity networks.|

Most of the files contain geometrical primitives that have been centered around the origin (0, 0, 0). The exception is the terrain file, which remains in the original coordinates downloaded from OpenStreetMaps. This type of file can be viewed with [QGIS](https://www.qgis.org/en/site/).