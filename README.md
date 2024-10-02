# Pian Exporter
The plugin exports the vector layer in WKT format, which is compatible with the Archaeological Map of the Czech Republic (PIAN). To use it, simply launch the plugin, select the layer you wish to export, and choose an output file with a .csv extension.

If the layer's geometry is in the EPSG:5514 (S-JTSK) or EPSG:4326 (WGS84) coordinate system, a CSV file will be created. If the geometry is in a different coordinate system, it will be converted to WGS84 before creating the CSV file.
