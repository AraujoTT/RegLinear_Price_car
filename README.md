# RegLinear_NYHouses
## Etapa1 - file: main.ipynb & data: Australian Vehicle prices.csv
        During this stage, data cleaning and necessary transformations were carried out for better performance.
    of the linear regression mechanism, cleaning such as deleting null or unfilled data, transformations such as
    exclusion of letters when filling out the database so that it is possible to transform the data into
    integers, making it possible to read them through the mechanisms.
        thus creating the clean_data.csv files for the complete database and also the clean_capping_data.csv
    regarding a database that was executing a price cut below 100 thousand to improve performance and
    create a more realistic data frame, thus removing supercars
## Etapa2  file: analisys.ipynb & data: clean_capping_data.csv
        Graphical analysis is performed and also numerical analysis to detect possible variations in the data or
    needs to implement some type of modification such as the one used in the dependent variable
    Price transforming it with log to obtain greater linearity in the dataset
        After modifications, clean_log_capping_data.csv was created
## Etapa3 file: linear_machine.ipynb data: clean_log_capping_data.csv
        Created linear regression analysis mechanism and generator of subsequent predictions obtaining accuracy
    of the mechanism developed and reaching a result of 70%
