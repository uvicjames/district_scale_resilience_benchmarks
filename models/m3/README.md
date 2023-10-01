# District-scale Resilience Benchmarks: Model 3

The first model contains a water distribution network that is layered on top of a synthetic block/street layout. The street network was created automatically by CityEngine, but it was subsequently edited by hand to clean up errors and create a more interesting parcel layout. There are no terrain files, as all geometry was defined on the z=0 plane.

<p align="center">
<img src="https://github.com/uvicjames/district_scale_resilience_benchmarks/assets/6242976/64632090-c4d5-4bf2-9fa4-5eff63d8743c" width="700">
</p>



# Model Files

The following files are currently included:

| File  | Description |
| ------------- | ------------- |
| _blocks.xml_  | an XML file that contains block and lot geometry.  |
|_buildings.obj_| an OBJ file that stores building geometry, as exported by CityEngine.|
| _streets.graphml_| a GraphML file that stores the street network.|
| _streets.obj_| an OBJ file that stores street geometry, as exported from CityEngine.|
| _water.graphml_|  a GraphML file that stores a water distribution network.|
|_vertices.xml_| an XML file that stores the original street network, as exported from CityEngine.|

Most of the files contain geometrical primitives that have been centered around the origin (0, 0, 0). The exception is the terrain file, which remains in the original coordinates downloaded from OpenStreetMaps. This type of file can be viewed with [QGIS](https://www.qgis.org/en/site/).
