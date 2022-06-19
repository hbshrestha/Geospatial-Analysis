# Geospatial-Analysis

## What's here?
This respository consists of the notebooks for following spatial analyses performed using Python. The main packages used are `geopandas`, `Matplotlib` and `NetworkX`.

|Topic|Data Source|
|-----|-----------|
|[Geoplotting emissions intensity of electricity generation in Europe](https://towardsdatascience.com/geoplotting-emissions-intensity-of-electricity-generation-in-europe-90c22b378858)|[Our World in Data 2021](https://ourworldindata.org/grapher/carbon-intensity-electricity)|
|[Exploring the demography and power sector of South Asia](https://towardsdatascience.com/exploring-the-demography-and-power-sector-of-south-asia-27cca720163c)|[World Bank Open Data 2021](https://data.worldbank.org/), [Our World in Data 2021](https://ourworldindata.org/electricity-mix)|
|[Network and interconnections in Python maps](https://towardsdatascience.com/network-and-interconnection-in-python-maps-6c797580b3b1)|[WorldPop 2022](https://www.worldpop.org/)|

- `script` consists of the Python notebooks for the above analyses.
- `data` consists of the data used in the notebooks.
- `output` contains the figures produced by the notebook, which are used in the analyses.

## Contributors
Himalaya Bir Shrestha

## Installation
- Download and clone this repository.

- Create a virtual environment using:
```
conda env create -n geospatial --file geospatial-environment.yml
```
- Once the environment is created, it can be activates using:
```conda activate geospatial```

- To create new kernel for jupyter notebook:
``` 
python -m ipykernel install --user --name geospatial --display-name "geospatial"
```

## Uninstallation
If the environment is not required any more, it can be removed using:
```conda env remove -n geospatial```

## Package requirements
Check `geospatial-environment.yml` file
