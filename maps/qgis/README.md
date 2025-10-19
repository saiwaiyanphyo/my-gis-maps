# QGIS Maps

This directory contains QGIS project files and related maps.

## Organization

Each map project should be in its own subdirectory with:
- QGIS project file (.qgz or .qgs)
- Project-specific README.md
- Any project-specific styling or configuration files

## Example Structure

```
qgis/
├── project-name-1/
│   ├── README.md
│   ├── project.qgz
│   └── styles/
└── project-name-2/
    ├── README.md
    └── project.qgz
```

## Tips

- Use relative paths in QGIS projects when possible
- Save projects in the compressed .qgz format
- Document any plugins or extensions required
