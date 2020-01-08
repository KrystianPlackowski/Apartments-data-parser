# Flat-data-parser
Extract data from flat advertisement web site and analyse it.

Both subfolders `rental` and `sale` containt strictly similar code with slightly different data source. Biggest differences in code between files `analyse.ipynb` in `sale` subfolder in comparision to file with the same name from `rental` subfolder are marked with red color or are crossed.

## rental
In this subfolder analysis is performed on `rental flat offers` (average prices in range 1500-5000 zł per flat).

## sale
In this subfolder analysis is performed on `sale flat offers` (average prices in range 250.000-1.000.000 zł per flat).

## predict_price
This subfolder uses pickled `mashine learning algorithms` learned in `rental`'s and `sale`'s `analyse.ipynb` file to experimentaly predict rental or sale prices on hand-typed data. Pickle files has to be first computed by running listed `analyse.ipynb` files.
