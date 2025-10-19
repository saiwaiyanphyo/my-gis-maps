# ArcGIS Maps

This directory contains ArcGIS project files and related maps.

## Organization

Each map project should be in its own subdirectory with:
- ArcGIS project file (.mxd for ArcMap, .aprx for ArcGIS Pro)
- Project-specific README.md
- Any project-specific styling or configuration files

## Example Structure

```
arcgis/
├── project-name-1/
│   ├── README.md
│   ├── project.aprx
│   └── styles/
└── project-name-2/
    ├── README.md
    └── project.mxd
```

## Tips

- Use relative paths in ArcGIS projects when possible
- Document the ArcGIS version used
- Note any extensions or toolboxes required
- Consider exporting layer files (.lyr) for complex symbology
