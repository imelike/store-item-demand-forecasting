# Store Item Demand Forecasting

A 3-month demand for a chain of stores, 10 different stores and 50 different products
asks for an estimate.

### Dataset Story

This dataset is presented to test different time series techniques. In the 5-year data of a chain of stores, 10 different stores and
Includes information on 50 different products. https://www.kaggle.com/competitions/demand-forecasting-kernels-only/data

| Sr. | Feature | Description              |
--- |---------|--------------------------| 
|1 | date    | Date of the sale data. There are no holiday effects or store closures. | 
|2 | store   | Store ID                 | 
|3 | item    | Item ID                  | 
|4 | sales   | Number of items sold at a particular store on a particular date. |


### Task
A 3-month demand forecasting model for the relevant store chain using the following time series and machine learning techniques
create it.
* Random Noise
* Lag/Shifted Features
* Rolling Mean Features
* Exponentially Weighted Mean Features
* Custom Cost Function (SMAPE)
* Model Validation with LightGBM