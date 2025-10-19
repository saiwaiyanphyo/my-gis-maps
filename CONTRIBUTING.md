# Contributing to My GIS Maps

Thank you for your interest in contributing to this GIS maps repository!

## How to Contribute

### Adding a New Map

1. **Create a project folder**
   - Navigate to the appropriate directory (`maps/qgis/` or `maps/arcgis/`)
   - Create a new folder with a descriptive name (use lowercase and hyphens)
   - Example: `population-density-analysis-2024`

2. **Add your project files**
   - Include the GIS project file (.qgz, .aprx, .mxd, etc.)
   - Add any custom styles or layer files
   - Include any project-specific scripts or tools

3. **Document your map**
   - Copy the template from `docs/templates/MAP_TEMPLATE.md`
   - Fill in all relevant sections
   - Include at least one preview image
   - Cite all data sources properly

4. **Export final maps**
   - Export your final map(s) to `maps/exports/`
   - Use standard formats (PNG, PDF, SVG)
   - Use descriptive filenames

### Adding Data

1. **Raw data**
   - Place original data in `data/raw/`
   - Organize by theme or source
   - Do not modify raw data

2. **Processed data**
   - Place processed data in `data/processed/`
   - Document all processing steps
   - Use the data documentation template

3. **Document your data**
   - Copy `docs/templates/DATA_TEMPLATE.md`
   - Fill in all relevant information
   - Include source, license, and CRS information

## Best Practices

### File Organization

- Use clear, descriptive folder and file names
- Use lowercase with hyphens for folder names
- Keep related files together
- Don't commit temporary or cache files

### Documentation

- Always include a README.md in project folders
- Document data sources and licenses
- Include creation dates and software versions
- Add notes about any special requirements

### Data Management

- Respect data licenses and usage rights
- Always cite data sources
- For large files (>100MB), consider Git LFS
- Don't commit proprietary or sensitive data

### Project Files

- Use relative paths when possible
- Keep projects self-contained
- Document any required plugins or extensions
- Test that projects open correctly

## Code of Conduct

- Be respectful and professional
- Give credit where credit is due
- Follow licensing requirements
- Maintain data integrity

## Questions?

If you have questions about contributing, please open an issue in this repository.
