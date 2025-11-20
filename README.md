# Private Rent Analysis: Deprivation and Rent Changes in England

Analysis for my [blog post](https://igdr.ch/posts/rent/) on rent in England.

## Visualizations

The analysis produces three main visualizations:

1. **Line Charts**: Cumulative rent change over time by region and local authority
2. **Choropleth Map**: Rent risk index showing areas most vulnerable to affordability issues
3. **Scatter Plot**: Relationship between deprivation (IMD) and rent change with trendline

## Files

- `final.ipynb` - Main analysis notebook
- `price_index_private_rent.xlsx` - Private rent index data
- `2025_deprivation_scores.xlsx` - Deprivation scores by local authority
- `boundaries` - Geographic boundary shapefiles

## Output Files

When run, the notebook generates:
- `private_rent_change_by_la.html` - Interactive line charts
- `rent_risk_index_map.html` - Interactive choropleth map  
- `imd_rent_scatter.html` - Interactive scatter plot with trendline

## Usage

1. Install required dependencies: `pip install -r requirements.txt`
2. [Download](https://geoportal.statistics.gov.uk/datasets/ons::local-authority-districts-may-2024-boundaries-uk-bfe-2/about) and extract boundaries to `boundaries` folder
2. Open `final.ipynb` in Jupyter Lab/Notebook or VS Code
3. Run all cells to reproduce the analysis

## Data Sources

- Private rent data: Office for National Statistics, [Private Rent and House Prices UK](https://www.ons.gov.uk/economy/inflationandpriceindices/bulletins/privaterentandhousepricesuk/october2025), October 2025
- Deprivation data: UK Ministry of Housing, Communities & Local Government, [Index of Multiple Deprivation](https://www.gov.uk/government/statistics/english-indices-of-deprivation-2025/english-indices-of-deprivation-2025-statistical-release), November 2025
- Geographic boundaries: Office for National Statistics, [Local Authority District boundaries](https://geoportal.statistics.gov.uk/datasets/ons::local-authority-districts-may-2024-boundaries-uk-bfe-2/about), May 2024