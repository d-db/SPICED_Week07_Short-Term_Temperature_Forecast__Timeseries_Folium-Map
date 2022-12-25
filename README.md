# SPICED Week07: Short-term temperature forecast and creating an interactive Folium map

## Project Summary

This project had two independent parts.

### Part 1: Create a short-term temperature forecast:

- Get and clean temperature data from www.ecad.eu (see file '1_decompose_timeseries.ipynb')
- Build a baseline model modelling trend and seasonality (see file '1_decompose_timeseries.ipynb')
- Plot and inspect the different components of a time series (see file '1_decompose_timeseries.ipynb')
- Model time dependence of the remainder using an AR model (see file '2_create_full_model.ipynb' and '3_evaluate.ipynb')
- Compare the statistical output of different AR models (see file '4_ARIMA.ipynb')

### Part 2: Create an interactive Folium map

- The map displays the average temperature change between 1970 and 2022 for each federal state in Germany (see file 'map.ipynb')

## Documentation

### Part 1: Create a short-term temperature forecast:

Plot the 'trend line'

![Bildschirmfoto 2022-12-25 um 20 45 32](https://user-images.githubusercontent.com/61935581/209480379-7410fbe0-0443-416f-9651-977dff2aec26.png)

Plot the 'trend line and seasonality'

![Bildschirmfoto 2022-12-25 um 20 46 42](https://user-images.githubusercontent.com/61935581/209480406-75dc0b1b-25ee-4f1a-ac50-f88a3c7f62e4.png)

Plot the 'remainder'

![Bildschirmfoto 2022-12-25 um 20 46 09](https://user-images.githubusercontent.com/61935581/209480434-cfdd3ba0-dae5-4acd-ac0e-f4bf8f31f02a.png)

Plot the trained model

![Bildschirmfoto 2022-12-25 um 20 47 44](https://user-images.githubusercontent.com/61935581/209480442-022c2a7f-9754-4f30-8806-1be64d56d25f.png)

### Part 2: Create an interactive Folium map

https://user-images.githubusercontent.com/61935581/209480492-481e6a9e-ce9a-4cda-afc6-8a8241b0aba1.mp4

## Contributing

Pull requests are welcome. For major changes, please open an issue firstto discuss what you would like to change.
Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)
