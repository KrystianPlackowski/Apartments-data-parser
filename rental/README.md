# Apartments-for-rental-parser

Extract data from well-known flat advertisement web site and make analysis out of it.


If want to extract new data:

- First run `extract_apart_data.ipynb` and `extract_metro_data.ipynb` notebooks to create `apartaments.csv` and `metro.csv` files.
- Secondly run `encode_travel_time.ipynb` to alter `apartaments.csv` by one additional column.

If want to analyse already prepared data (doesn't have sensitive informations):

- Run `analyse.ipynb` with provided `apartaments.csv` and `metro.csv` files to further processed them. *Prepared data was collected on 25.12.19*


What provided notebook files actually do:

`extract_apart_data.ipynb` extracts apartaments data from the site to .csv file. **The data concerns only rental offers**

`extract_metro_data.ipynb` returns .csv file of list of Warsaw metro stations with their geographic locations

`encode_travel_time.ipynb` encodes travel times from locations of apartaments to city center point (PKiN) using public transport

geojson source:
https://zikit.carto.com/tables/warszawa_dzielnice/public/map

api provider site for travel time encoding (free registration):
https://developer.here.com/
