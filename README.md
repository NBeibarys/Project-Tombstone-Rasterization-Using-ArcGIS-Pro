# Tombstone Rasterization
This project demonstrates practical GIS data creation, cleaning, and rasterization techniques using ArcGIS Pro. The goal was to produce a 1-meter resolution raster map of Tombstone, Arizona, encoding land-use classes for soil, roads, and buildings.

## Project Structure
- `Tombstone.pdf` - Final map output including legend, scale, and author details.
- `Tombstone.mpkx` - ArcGIS Pro project file containing all feature classes, rasters, and map layouts.
- `Deliverable` - A 3-part data visualization illustrating the relationship between critical reception, audience sentiment, and return on investment (ROI).

## Key Insights
- Repaired invalid geometries in building features and reconstructed missing areas using the *Reshape* tool.  
- Created new line feature classes for roads, ensuring consistent projections and attribute structures.  
- Applied *Feature to Raster*, *Reclassify*, and *Raster Calculator* tools to convert and combine vector layers into a 1 m resolution raster dataset.  
- Produced a clean raster map suitable for further land-use or environmental analysis.
  
## Tools & Technologies
 - **ArcGIS Pro - Raster Calculator, Reclassify** 
- **QGIS**

## Deliverable 
[![map](Tombstone_preview.jpg)](Tombstone.pdf)
