# Shapefile Buffer and Uncertainty Area Calculator

This repository contains a simple Python script that loads a glacier outline shapefile, applies buffer operations to estimate spatial uncertainty, and calculates the corresponding areas.

## Features

* Load a glacier outline shapefile using `GeoPandas`
* Reproject to a UTM coordinate system (EPSG:32620)
* Generate positive and negative buffer zones (±0.5 m)
* Calculate:

  * Original area
  * Buffered areas
  * Uncertainty zone (difference between outer and inner buffers)

## Example Output

```text
Original area (km²): 8.35  
Positive buffer area (km²): 8.74  
Negative buffer area (km²): 7.95  
Area of uncertainty (km²): 0.79
```

