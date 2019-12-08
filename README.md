# Car Price Prediction project (Python)
## Problem Statement
A Chinese automobile company Geely Auto aspires to enter the US market by setting up their manufacturing unit there and producing cars locally to give competition to their US and European counterparts.

They have contracted an automobile consulting company to understand the factors on which the pricing of cars depends. Specifically, they want to understand the factors affecting the pricing of cars in the American market, since those may be very different from the Chinese market.

## Methodology
- Data Wrangling
- Exploratory Data Analysis
- Data Visualization
- Machine Learning Algorithm used - Linear Regression
- Evaluation metric used : R2 score

## Technologies/Libraries used
- Python 3
- Numpy
- Pandas
- sklearn
- Seaborn
- Matplotlib
- statsmodels

## Variables used to make the predictions
- **symboling** : Assigned insurance risk rating
- **fueltype** : Car fuel type i.e gas or diesel
- **aspiration** : Aspiration used in a car
- **wheelbase** : Weelbase of car
- **carlength** : Length of car
- **carwidth** : Width of car
- **curbweight** : The weight of a car without occupants or baggage
- **enginetype** : Type of engine
- **cylindernumber** : Cylinder placed in the car
- **enginesize** : Size of car
- **boreratio** : Boreratio of car
- **horsepower** : Horsepower of car
- **carbody** : Body of car (Convertible, Hatchback, Sedan, etc.)
- **company** : Name of car company
- **drivewheel** : Type of drive wheel

## Summary
_The final linear regression model gave a R2 score of 86% with the equation of the best fitted line as_ **𝑝𝑟𝑖𝑐𝑒=0.72×ℎ𝑜𝑟𝑠𝑒𝑝𝑜𝑤𝑒𝑟−0.051×𝑐𝑎𝑟𝑏𝑜𝑑𝑦_ℎ𝑎𝑡𝑐ℎ𝑏𝑎𝑐𝑘+0.3×𝑐𝑜𝑚𝑝_𝑏𝑚𝑤+0.42×𝑐𝑜𝑚𝑝_𝑏𝑢𝑖𝑐𝑘+0.314×𝑐𝑜𝑚𝑝_𝑗𝑎𝑔𝑢𝑎𝑟+0.174×𝑐𝑜𝑚𝑝_𝑝𝑜𝑟𝑠𝑐ℎ𝑒+0.127×𝑐𝑜𝑚𝑝_𝑣𝑜𝑙𝑣𝑜**
