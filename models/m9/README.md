# District-scale Resilience Benchmarks: Model 8

This model contains a water distribution network that is defined upon a small, artificial block/lot/street layout. There is no terrain file, and all vertices are on the z=0 plane.

<p align="center">
<img src="https://github.com/uvicjames/district_scale_resilience_benchmarks/assets/6242976/333ebaff-dc61-41b9-86d3-ef9af875b3aa" width="600">
</p>


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
