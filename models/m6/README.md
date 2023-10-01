# District-scale Resilience Benchmarks: Model 6

This model contains an electricity network and a water distribution network that are defined upon a small, artificial block/lot/street layout. This model is built on a terrain.

<p align="center">
<img src="https://github.com/uvicjames/district_scale_resilience_benchmarks/assets/6242976/ccf729a0-6c8b-4a14-971d-0972733370c8" width="600">
</p>

# Model Files

The following files are currently included:

| File  | Description |
| ------------- | ------------- |
| _blocks.xml_  | an XML file that contains block and lot geometry  |
|_buildings.obj_| an OBJ file that stores building geometry, as exported by CityEngine.|
| _streets.graphml_| a GraphML file that stores the street network.|
| _streets.obj_| an OBJ file that stores the street geometry, as exported by CityEngine.|
| _interconnects.xml_| an XML file that defines physical dependencies between nodes in the water and electricity networks.|

All geometry is centered around the origin (0, 0, 0). Users should not expect it to match empirical data in terms of scale or coordinates. 
