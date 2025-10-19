# My GIS Maps Collection

A repository for storing and organizing GIS maps created using QGIS and ArcGIS.

## Overview

This repository contains geospatial visualizations and analysis projects created with professional GIS software including QGIS and ArcGIS.

## Repository Structure

```
my-gis-maps/
├── maps/                 # Main directory for all GIS maps
│   ├── qgis/            # QGIS projects and maps
│   ├── arcgis/          # ArcGIS projects and maps
│   └── exports/         # Exported maps (PNG, PDF, etc.)
├── data/                # Geospatial data files
│   ├── raw/             # Original/raw data
│   └── processed/       # Processed data
├── docs/                # Documentation and metadata
│   └── templates/       # Templates for map metadata
└── README.md            # This file
```

## Getting Started

### Prerequisites

- **QGIS** (version 3.x or higher) - [Download](https://qgis.org/en/site/forusers/download.html)
- **ArcGIS** (Desktop or Pro) - Optional for ArcGIS projects

### Adding a New Map

1. Create a new folder under the appropriate directory (`maps/qgis/` or `maps/arcgis/`)
2. Name the folder descriptively (e.g., `population-density-2024`)
3. Add your GIS project files to the folder
4. Include a README.md in the map folder with:
   - Map title and description
   - Data sources
   - Creation date
   - Software and version used
   - Any special notes or instructions

### Data Management

- Place raw geospatial data in `data/raw/`
- Store processed/cleaned data in `data/processed/`
- For large files (>100MB), consider using [Git LFS](https://git-lfs.github.com/)
- Always document data sources and licensing

## Map Metadata Template

For each map project, include a README.md with:

```markdown
# [Map Title]

**Created:** [Date]
**Software:** [QGIS/ArcGIS version]
**Author:** [Your name]

## Description
Brief description of what the map shows

## Data Sources
- Source 1: [Name and URL]
- Source 2: [Name and URL]

## Layers
- Layer 1: Description
- Layer 2: Description

## Export Formats
- Format 1 (location)
- Format 2 (location)
```

## File Formats

Common file formats in this repository:

- **Vector:** `.shp` (Shapefile), `.geojson`, `.gpkg` (GeoPackage)
- **Raster:** `.tif`, `.tiff`, `.img`
- **Projects:** `.qgz` (QGIS), `.qgs` (QGIS Legacy), `.mxd` (ArcMap), `.aprx` (ArcGIS Pro)
- **Exports:** `.png`, `.pdf`, `.svg`

## Contributing

When adding new maps:

1. Follow the folder structure
2. Include proper documentation
3. Cite all data sources
4. Export final maps to `maps/exports/`
5. Keep project files organized and clean

## License

Please specify the license for your maps and respect the licenses of any data sources used.

## Contact

For questions or suggestions, please open an issue in this repository.
