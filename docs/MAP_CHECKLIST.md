# Map Addition Checklist

Use this checklist when adding a new map to ensure you've included everything.

## Before Adding Your Map

- [ ] Project is complete and finalized
- [ ] All data sources are properly cited
- [ ] Project opens correctly in the GIS software
- [ ] Final map has been exported

## Adding the Map

- [ ] Created project folder in `maps/qgis/` or `maps/arcgis/`
- [ ] Used descriptive folder name (lowercase-with-hyphens)
- [ ] Copied project files to folder
- [ ] Added any custom styles or symbols

## Documentation

- [ ] Copied MAP_TEMPLATE.md to project folder as README.md
- [ ] Filled in map title and description
- [ ] Added creation date and last update date
- [ ] Specified software and version
- [ ] Listed all data sources with URLs
- [ ] Described all layers in the map
- [ ] Documented the CRS (coordinate reference system)
- [ ] Noted any processing steps
- [ ] Added preview image
- [ ] Documented export settings

## Data Management

- [ ] Placed raw data in `data/raw/` (if not already there)
- [ ] Placed processed data in `data/processed/` (if applicable)
- [ ] Created data documentation using DATA_TEMPLATE.md
- [ ] Verified data licenses allow repository inclusion
- [ ] Checked file sizes (consider Git LFS for files >100MB)

## Exports

- [ ] Exported final map to `maps/exports/`
- [ ] Created PNG version (for web/documentation)
- [ ] Created PDF version (for printing, if needed)
- [ ] Created SVG version (if applicable)
- [ ] Used descriptive filename
- [ ] Documented export settings in README

## Quality Check

- [ ] All file paths are relative (where possible)
- [ ] Project opens without errors
- [ ] README is complete and accurate
- [ ] All links work correctly
- [ ] Preview image displays correctly
- [ ] Spelling and grammar checked

## Git

- [ ] Reviewed changes with `git status`
- [ ] Added appropriate files with `git add`
- [ ] Checked that no temporary files are included
- [ ] Created descriptive commit message
- [ ] Pushed changes to repository

## Optional Enhancements

- [ ] Added methodology notes for complex analysis
- [ ] Included scale bar and north arrow in exports
- [ ] Created multiple versions (different styles/themes)
- [ ] Added related analysis or reports
- [ ] Linked to related projects

---

## Quick Reference

**Folder naming**: Use lowercase with hyphens (e.g., `my-map-project`)

**Required files per map**:
- Project file (.qgz, .aprx, .mxd, etc.)
- README.md with documentation
- At least one exported image

**Required information**:
- Title, description, date
- Software and version
- Data sources with URLs
- CRS information
- Layer descriptions
