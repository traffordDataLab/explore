# explore
[Explore](https://www.trafforddatalab.io/explore) is an interactive map application built by [Trafford Data Lab](https://www.trafforddatalab.io) to visualise spatial datasets relating to Trafford.  It uses the following technologies:

- [**Leaflet JS**](https://leafletjs.com/) JavaScript mapping library
- [**Lab_leaflet**](https://github.com/traffordDataLab/lab_leaflet) our Leaflet JS wrapper library
- [**Leaflet.reachability**](https://github.com/traffordDataLab/leaflet.reachability) our reachability Leaflet plugin which uses the [isochrones API](https://openrouteservice.org/dev/#/api-docs) from [OpenRouteService](https://openrouteservice.org/)
- [**Leaflet.Locate**](https://github.com/domoritz/leaflet-locatecontrol) Leaflet plugin
- [**Leaflet.markercluster**](https://github.com/Leaflet/Leaflet.markercluster) Leaflet plugin
- [**Mapbox GL JS**](https://docs.mapbox.com/mapbox-gl-js/api/) JavaScript library
- [**Mapbox-gl-leaflet**](https://github.com/mapbox/mapbox-gl-leaflet) [(our customised fork)](https://github.com/traffordDataLab/mapbox-gl-leaflet) JavaScript binding from Mapbox GL JS to the Leaflet API
- [**OS Zoomstack**](https://www.ordnancesurvey.co.uk/business-and-government/products/os-open-zoomstack.html) Ordnance Survey vector tiles
- [**OpenStreetMap**](https://www.openstreetmap.org/#map=5/54.910/-3.432) raster tiles
- [**CartoDB**](https://github.com/CartoDB/basemap-styles) raster tiles

The datasets available to the application are described within the [JSON](https://www.json.org/) meta file [datasets.json](https://github.com/traffordDataLab/explore/blob/master/datasets.json) and stored within our [open_data](https://github.com/traffordDataLab/open_data) repository.

To display a particular dataset when the application loads, add `?dataset=` followed by the dataset key from the meta file to the URL. For example, [https://www.trafforddatalab.io/explore/?dataset=green_spaces](https://www.trafforddatalab.io/explore/?dataset=green_spaces) will display the green spaces dataset from Ordnance Survey.
