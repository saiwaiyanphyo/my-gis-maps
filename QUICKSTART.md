# Quick Start Guide

Welcome to your GIS Maps repository! This guide will help you quickly add your first map.

## Adding Your First Map

### Step 1: Choose Your Directory

Decide whether this is a QGIS or ArcGIS project:
- QGIS projects → `maps/qgis/`
- ArcGIS projects → `maps/arcgis/`

### Step 2: Create a Project Folder

```bash
# Example for a QGIS project
cd maps/qgis/
mkdir my-first-map
cd my-first-map
```

### Step 3: Add Your Files

Copy your project files into this folder:
- `.qgz` or `.qgs` files (QGIS)
- `.aprx` or `.mxd` files (ArcGIS)
- Any style files or custom symbols

### Step 4: Document Your Map

Copy the template and fill it in:

```bash
cp ../../../docs/templates/MAP_TEMPLATE.md README.md
# Edit README.md with your map details
```

Required information:
- Map title and description
- Date created
- Software version
- Data sources (with URLs)
- Layer descriptions

### Step 5: Export Your Map

1. Export your final map in at least PNG format
2. Save to `../../exports/[your-project-name]/`
3. Include the export path in your README

### Step 6: Add Data Documentation

If you're adding new datasets:

```bash
cd ../../../data/raw/
mkdir my-dataset
# Copy your data files
# Document using DATA_TEMPLATE.md
```

## Common Tasks

### Adding Multiple Maps

Repeat the above steps for each map project. Keep each project in its own folder.

### Organizing Exports

Create folders by date or project:

```bash
maps/exports/2024/january/my-map.png
# or
maps/exports/by-project/my-first-map/final.png
```

### Managing Large Files

For files over 100MB:
1. Consider Git LFS: `git lfs install`
2. Track large files: `git lfs track "*.tif"`
3. Or link to external storage in documentation

### Updating Existing Maps

1. Update the project files
2. Update the README with changes and new date
3. Create new exports with version numbers or dates

## Tips for Success

- ✅ **Use descriptive folder names**: `population-density-2024` not `map1`
- ✅ **Always document data sources**: Include URLs and download dates
- ✅ **Export in multiple formats**: PNG for web, PDF for print
- ✅ **Keep projects self-contained**: Use relative paths when possible
- ✅ **Update documentation**: Keep README files current

## Example Structure

After adding a few maps, your repository might look like:

```
my-gis-maps/
├── maps/
│   ├── qgis/
│   │   ├── population-density-2024/
│   │   │   ├── README.md
│   │   │   ├── project.qgz
│   │   │   └── preview.png
│   │   └── land-use-analysis/
│   │       ├── README.md
│   │       └── project.qgz
│   └── exports/
│       ├── population-density-2024.png
│       └── land-use-analysis.pdf
└── data/
    └── raw/
        ├── census-data/
        └── land-parcels/
```

## Need Help?

- Check the main [README.md](README.md) for detailed information
- Review the [CONTRIBUTING.md](CONTRIBUTING.md) for best practices
- Look at the templates in `docs/templates/`

## Next Steps

1. Add your first map following this guide
2. Export it to the exports folder
3. Document any datasets you use
4. Repeat for additional maps!

Happy mapping! 🗺️
