# Area Code Analysis

This project analyzes the demographic and geographical patterns in telephone area code assignments across the United States. The analysis explores the relationship between population density, demographics, and the distribution of area codes.

## Project Structure

- `Project.qmd`: Quarto document containing the analysis code and documentation
- `Project.html`: HTML output of the analysis
- `final_project_data/`: Directory containing datasets used in the analysis
  - `cities_area_codes.csv`: Dataset linking cities to their area codes
  - `county_census_info.csv`: Census information for counties
  - `merged_counties_since_1950.csv`: Information on counties that have merged since 1950
  - `new_counties_since_1950.csv`: Information on new counties formed since 1950
  - `splits_overlays.xlsx`: Data on area code splits and overlays
  - `co99_d00_shp/`: Shapefile data for county boundaries

## Visualizations

The `Project_files/figure-html/` directory contains various visualizations created as part of the analysis, including:
- Population distribution maps
- Area code distribution maps
- Regression analysis plots
- Demographic correlation visualizations

## How to Use

Open the `Project.html` file to view the complete analysis with visualizations. The `Project.qmd` file can be opened and modified in RStudio or any Quarto-compatible editor to reproduce or extend the analysis.

## Technologies Used

- R for statistical analysis
- Quarto for document preparation
- Spatial analysis libraries for geographical mapping
