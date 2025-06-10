# Political-Dynasties-and-Poverty-Incidence

Contributors
- Barra, Giane Gwyneth
- Estiller, Ma. Mechaela
- Gutang, John Lloyd
- Mariano, Belinda Rose
- Mendoza, Gwyneth Nicole

This project explores the relationship between political dynasties and poverty incidence in the Philippines using data analysis and geospatial visualization. The dataset includes poverty rates from 2003 to 2021 and political family composition across regions.

# Requirements
- pip install numpy pandas statsmodels linearmodels matplotlib seaborn openpyxl
- pip install geopandas sphfile networkx pyvis ipython scipy
- pip install --upgrade pandas linearmodels
- pip install python-louvain

# Code Summary
1. Data Preparation
Load poverty and political dynasty datasets.
Merge datasets and align regional labels.
Generate full names for dynasty tracking.

2. Geospatial Analysis
Load Philippine shapefiles using geopandas.
Visualize poverty incidence per region from 2003 to 2021.
Highlight top 5 poorest regions per year with custom legends.

3. Statistical Analysis
Prepare datasets for regression analysis.
Explore relationship between "fat dynasties" and poverty over time.
Use PanelOLS and other models from linearmodels for regression.

# Output
- Series of maps showing poverty incidence by region.
- Regression summaries evaluating influence of political dynasties on poverty.
- Visualizations created with matplotlib, geopandas, and seaborn.

# Key Libraries
- pandas, numpy — Data handling
- statsmodels, linearmodels — Econometric modeling
- geopandas, matplotlib, seaborn — Visualization
- networkx, pyvis, community_louvain — Political network analysis (optional extensions)

  # Notes
- Ensure that the shapefile and poverty data CSV are properly formatted and aligned with the region names used in the analysis.
- Run the notebooks/cells sequentially to avoid dependency issues.
