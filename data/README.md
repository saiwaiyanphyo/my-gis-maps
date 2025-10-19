# Geospatial Data

This directory contains the geospatial data used in map projects.

## Subdirectories

### `raw/`
Original, unmodified geospatial data from various sources.

### `processed/`
Data that has been cleaned, transformed, or processed for use in map projects.

## Data Organization

Organize data by theme or source:

```
data/
├── raw/
│   ├── administrative-boundaries/
│   ├── population/
│   └── infrastructure/
└── processed/
    ├── administrative-boundaries/
    ├── population/
    └── infrastructure/
```

## Data Documentation

For each dataset, include:
- Source and URL
- Download date
- License/usage rights
- Coordinate reference system (CRS)
- Processing steps (if applicable)

## Large Files

For files larger than 100MB:
- Consider using Git LFS
- Or store externally and link in documentation
- Document where to obtain large datasets

## Data Formats

Common formats:
- **Vector**: Shapefile (.shp + .dbf, .shx, .prj), GeoJSON (.geojson), GeoPackage (.gpkg)
- **Raster**: GeoTIFF (.tif, .tiff), IMG (.img)
- **Tabular**: CSV with coordinates, Excel with geospatial data
