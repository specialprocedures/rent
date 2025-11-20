# Private Rent Analysis: Deprivation and Rent Changes in England

This analysis examines the relationship between deprivation levels and private rent changes across English local authorities from 2020-2025.

## Overview

The analysis combines:
- Private rent index data (2020-2025)
- Index of Multiple Deprivation (IMD) scores (2025)
- Geographic boundary data for local authorities

## Key Findings

- **Rent Risk Index**: Areas with high rent increases combined with high income deprivation present the greatest affordability challenges
- **Regional Variation**: Rent changes vary significantly across regions, with some areas experiencing increases of 60%+ over the period
- **Deprivation Correlation**: Higher deprivation scores are associated with faster rent increases on average

## Visualizations

The analysis produces three main visualizations:

1. **Line Charts**: Cumulative rent change over time by region and local authority
2. **Choropleth Map**: Rent risk index showing areas most vulnerable to affordability issues
3. **Scatter Plot**: Relationship between deprivation (IMD) and rent change with trendline

## Files

- `final.ipynb` - Main analysis notebook
- `price_index_private_rent.xlsx` - Private rent index data
- `2025_deprivation_scores.xlsx` - Deprivation scores by local authority
- `Local_Authority_Districts_May_2024_Boundaries_UK_BFE_*/` - Geographic boundary shapefiles

## Output Files

When run, the notebook generates:
- `private_rent_change_by_la.html` - Interactive line charts
- `rent_risk_index_map.html` - Interactive choropleth map  
- `imd_rent_scatter.html` - Interactive scatter plot with trendline

## Usage

1. Install required dependencies: `pip install -r requirements.txt`
2. Open `final.ipynb` in Jupyter Lab/Notebook or VS Code
3. Run all cells to reproduce the analysis

## Corporate Styling

All visualizations use a consistent color scheme:
- Beige background: `rgb(244, 240, 231)`
- Cyan highlights: `rgb(10, 255, 206)`
- Dark blue emphasis: `rgb(21, 38, 58)`

## Data Sources

- Private rent data: UK Government rent index statistics
- Deprivation data: UK Government Index of Multiple Deprivation 2025
- Geographic boundaries: ONS Local Authority District boundaries (May 2024)