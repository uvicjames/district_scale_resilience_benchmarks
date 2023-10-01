# District-scale Resilience Benchmarks: Model 7

A model of a portion of the Silver Firs neighborhood in Sonohomish County, Washington, United States. This model contains an electricity network and a water distribution network that are defined upon an empirical street layout. The street network and terrain data were acquired from OpenStreetMaps.

<p align="center">
<img src="https://github.com/uvicjames/district_scale_resilience_benchmarks/assets/6242976/f629a239-44ef-436b-be90-8f215a6e1c7e" width="600">
</p>


# Model Files

The following files are currently included:

| File  | Description |
| ------------- | ------------- |
| _blocks.xml_  | an XML file that contains block and lot geometry  |
|_buildings.obj_| an OBJ file that stores building geometry, as exported by CityEngine.|
| _streets.graphml_| a GraphML file that stores the street network.|
| _streets.obj_| an OBJ file that stores the street geometry, as exported by CityEngine.|
|_terrain.tif_|	a geotiff file that represents the terrain.|
|_terrain.obj_|	an OBJ file that contains geometry for the terrain.|
| _interconnects.xml_| an XML file that defines physical dependencies between nodes in the water and electricity networks.|

All geometry is centered around the origin (0, 0, 0). Users should not expect it to match empirical data in terms of scale or coordinates. 

