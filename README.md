# Geospatial-Analysis

This respository consists of the following spatial analyses performed using Python. The main packages used are [geopandas](https://geopandas.org/en/stable/) and [matplotlib](https://matplotlib.org/).

|Topic|Data Source|
|-----|-----------|
|[Geoplotting emissions intensity of electricity generation in Europe](https://towardsdatascience.com/geoplotting-emissions-intensity-of-electricity-generation-in-europe-90c22b378858)|[Our World in Data 2021](https://ourworldindata.org/grapher/carbon-intensity-electricity)|
|[Exploring the demography and power sector of South Asia](https://towardsdatascience.com/exploring-the-demography-and-power-sector-of-south-asia-27cca720163c)|[World Bank Open Data 2021](https://data.worldbank.org/), [Our World in Data 2021](https://ourworldindata.org/electricity-mix)|
|Network and interconnections in Python maps|[WorldPop 2022](https://www.worldpop.org/)|


# Installation
```
conda env create -n geospatial --file geospatial-environment.yml
conda activate geospatial
```
## To create new kernel for jupyter notebook:
``` 
python -m ipykernel install --user --name <python environment> --display-name "Python (<python environment>)"
```

## Package requirements
The packages required for running the script are as follows:
- pandas
- matplotlib
- geoplot
- geopandas (version 0.8.2 or above)
- shapely
- plotly
- networkx
