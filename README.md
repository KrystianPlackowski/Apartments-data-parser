# Apartments-data-parser
Extract data from flat advertisement web site and analyse it. This project has 4 parts:
1) extract data using `requests, beatifulsoup`
2) encoded travel time with `route API`
3) present relations between `location, travel time, apartment's size` and `price`
4) develop `scikit-learn model` to `predict price`

Both subfolders `rental` and `sale` contain strictly similar code with slightly different data source. The differences are only between files `analyse.ipynb` in `sale` and `rental` subfolders and are marked with red color or crossed text.

## rental
In this subfolder analysis is performed on `rental flat offers` (average prices in range 1500-5000 zł per flat).

## sale
In this subfolder analysis is performed on `sale flat offers` (average prices in range 250.000-1.000.000 zł per flat).

## predict_price
This subfolder uses pickled `mashine learning algorithms`, which can be learned by first running files `analyse.ipynb` from `rental` and `sale` subfolders. The goal of the algorithm is to predict rental or sale prices of apartaments. **Interactive data typing is already supported.**
