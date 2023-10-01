# District-scale Resilience Benchmarks: Model 10

This model contains a water distribution network for the village of Frewsburg, Chautauqua County, New York, United States. Data obtained from OpenStreetMaps, WGS 1984 UTM Zone 17N. There is no terrain file, and all vertices are on the z=0 plane.

Electricity and ICT networks will be added at a later date.

# Model Files

The following files are currently included:

| File  | Description |
| ------------- | ------------- |
| _blocks.xml_  | an XML file that contains block and lot geometry  |
|_buildings.obj_| an OBJ file that stores building geometry, as exported by CityEngine.|
| _streets.graphml_| a GraphML file that stores the street network.|
| _streets.obj_| an OBJ file that stores the street geometry, as exported by CityEngine.|
| _water.graphml_|  a GraphML file that stores a water distribution network.|
| _interconnects.xml_| an XML file that defines physical dependencies between nodes in the water and electricity networks.|

All geometry is centered around the origin (0, 0, 0). Users should not expect it to match empirical data in terms of scale or coordinates. 
