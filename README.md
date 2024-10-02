# AMČR Pian Exporter
The plugin exports the vector layer in the WKT format, which is compatible with the Archaeological Map of the Czech Republic (PIAN). To use it, simply start the plugin, select the layer you want to export and choose an output file with a .csv extension.

If the geometry of the layer is in the EPSG:5514 (S-JTSK) or EPSG:4326 (WGS84) coordinate system, a CSV file will be created. If the geometry is in another coordinate system, it will be converted to WGS84 before the CSV file is created.
