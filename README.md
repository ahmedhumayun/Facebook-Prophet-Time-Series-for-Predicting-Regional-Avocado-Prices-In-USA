# Facebook Prophet Time Series for Predicting Regional Avocado Prices In USA

The objective of this project is to predict regional avocado prices in USA using a historical dataset.


Using the dataset I have tried to answer the following questions using Facebooks Prophet Time Series Analysis-

(1) What is the monthly future prediction of the regional avocado prices in USA? (Ipython notebook)

(2) During which months does avocado prices peak go up during the year? (Ipython notebook)

(3) Compare the regional avocado price trends in USA vs individual regions (California, Midwest, Northeast, Southeast etc.)

# Dataset

Data represents weekly 2018 retail scan data for National retail volume (units) and price.
Retail scan data comes directly from retailers’ cash registers based on actual retail sales of Hass avocados.
The Average Price (of avocados) in the table reflects a per unit (per avocado) cost, even when multiple units (avocados) are sold in bags.
The Product Lookup codes (PLU’s) in the table are only for Hass avocados. Other varieties of avocados (e.g. greenskins) are not included in this table.

Some relevant columns in the dataset:

    Date - The date of the observation
    AveragePrice - the average price of a single avocado
    type - conventional or organic
    year - the year
    Region - the city or region of the observation
    Total Volume - Total number of avocados sold
    4046 - Total number of avocados with PLU 4046 sold
    4225 - Total number of avocados with PLU 4225 sold
    4770 - Total number of avocados with PLU 4770 sold


# Facebook Prophet 

Prophet is open source software released by Facebook’s Core Data Science team.

Prophet is a procedure for forecasting time series data based on an additive model where non-linear trends are fit with yearly, weekly, and daily seasonality, plus holiday effects.

Prophet works best with time series that have strong seasonal effects and several seasons of historical data.
For more information, please check this out: https://research.fb.com/prophet-forecasting-at-scale/ https://facebook.github.io/prophet/docs/quick_start.html#python-api

