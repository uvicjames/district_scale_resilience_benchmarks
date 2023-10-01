# District-scale Resilience Benchmarks: Model 1

The first model contains an electricity network and a water distribution network created from a street network located in Jamestown, New York. The terrain and street layout were obtained from OpenStreetMaps (WGS 84 / UTM zone 17N) by way of ESRI CityEngine. An overview of the main networks is shown below:


<p align="center">
<img src="https://github.com/uvicjames/district_scale_resilience_benchmarks/assets/6242976/dfef8183-5a80-4c8f-a879-7b120f778d9b" width="700">
</p>

Please note that there are issues with the z-axis (i.e., height). The infrastructure networks are not snapping to the terrain file at present.

# Model Files

The following files are currently included:

| File  | Description |
| ------------- | ------------- |
| _blocks.xml_  | an XML file that contains block and lot geometry  |
| _streets.graphml_| a GraphML file that stores the street network.|
| _water.graphml_|  a GraphML file that stores a water distribution network.|
| _electricity.graphml_| a GraphML file that stores a low-voltage ("LV") electricity network.|
| _terrain.tif_| a geotiff file that represents the terrain.|
| _interconnects.xml_| an XML file that defines physical dependencies between nodes in the water and electricity networks.|

Most of the files contain geometrical primitives that have been centered around the origin (0, 0, 0). The exception is the terrain file, which remains in the original coordinates downloaded from OpenStreetMaps. This type of file can be viewed with [QGIS](https://www.qgis.org/en/site/).
