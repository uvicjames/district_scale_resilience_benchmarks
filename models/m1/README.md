# District-scale Resilience Benchmarks: Model 1

The first model contains an electricity network and a water distribution network. The terrain and street layout were obtained from OpenStreetMaps by way of ESRI CityEngine. An overview of the main networks is shown below:


<p align="center">
<img src="https://github.com/uvicjames/district_scale_resilience_benchmarks/assets/6242976/72984ec1-7b85-4d59-9198-42c457ddaaf1" width="700">
</p>



# Model Files

The following files are present:
- _blocks.xml_: an XML file that contains block and lot geometry.
- _streets.graphml_: a GraphML file that stores the street network.
- _water.graphml_:  a GraphML file that stores a water distribution network.
- _electricity.graphml_: a GraphML file that stores a low-voltage ("LV") electricity network.
- _terrain.tif_: a geotiff file that represents the terrain (WGS 84 / UTM zone 17N). 

Most of the files contain geometrical primitives that have been centered around the origin (0, 0, 0). The exception is the terrain file, which remains in the original coordinates downloaded from OpenStreetMaps. This type of file can be viewed with [QGIS](https://www.qgis.org/en/site/).
