# Bike Sharing Assignment
> Building a Linear Regression model to identify the significant variables in predicting the demand for shared bikes


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)


## General Information
This is an assignment in which we use Python to build a Linear Regression model to understand BoomBikes - a US bike-sharing provider.

In this project, we need to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations.

We use the `bike_dataset.csv` (included in this repository) to build the model.

## Conclusions
Those are the conclusions retrieved from the model, further information can be found in the Notebook

After our final model, we can see the top predictor variables:
- **Temperature** `temp` has a coefficient value of 0.5038, which indicates that it is a strong predictor variable influence the shared bike demand
- **Year** `yr` has a coefficient value of 0.2390, that means the demand for shared bike will increase as year increase
- **Windspeed** `windspeed` has a coefficient value of -0.1777, indicates that strong wind will affect the booking of shared bikes


## Technologies Used
- `python` - version 3.9
- `pandas` - version 1.4.3
- `notebook` - version 6.4.12
- `matplotlib` - version 3.5.2
- `seaborn` - version 0.11.2
- `scikit-learn` - version 1.1.2
- `statsmodels` - version 0.13.2

## Contact
Created by [@phucanthony] - feel free to contact me!

