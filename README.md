# Health-Care-Analysis

## Intro

In this project it will be introduced an analysis refering to the relation between Health Care expenses and Life Expentancy among different countries.

It is important to know the balance between having a robust health care system and life expentancy. That is why it will be studied the impact in society that this two areas have through the data retrieved in different fields, such as cost of life, in order to make a ranking and cluster around one houndred countries into different groups. This way, it can be obtained the performance of the health care system in each country and thus, the impact in society.

## Structure of the project

* Retrieve Data
* Clean Data
* Normalyze & Analyze Data
* Display Results & Apply ML Tools

## Prerequisites

What things you need to install the software and how to install them.

```
!conda install numpy
import numpy as np

!conda install pandas
import pandas as pd 
pd.set_option('display.max_columns', None)
pd.set_option('display.max_rows', None)

!conda install json
import json 

!conda install -c conda-forge geopy --yes 
from geopy.geocoders import Nominatim 

import requests # library to handle requests
from pandas.io.json import json_normalize # tranform JSON file into a pandas dataframe

!conda install matplotlib
import matplotlib.cm as cm
import matplotlib.colors as colors

# import k-means from clustering stage
from sklearn.cluster import KMeans

!conda install -c conda-forge folium=0.5.0 --yes
import folium # map rendering library
```

## Data Needed

Which Data is required to perform the research.

### Wikipidia expenses per capita in health care per country

```
https://en.wikipedia.org/wiki/List_of_countries_by_total_health_expenditure_per_capita
```

### Numbeo cost of living ranking

```
https://www.numbeo.com/cost-of-living/rankings_by_country.jsp
```

### Wikipedia life expentancy per country
```
https://en.wikipedia.org/wiki/List_of_countries_by_life_expectancy
```

### Foursquare location / Google Geodata Location 

```
https://developers.google.com/public-data/docs/canonical/countries_csv
```
## Built With

* Jupiter Notebook 6.0.1




