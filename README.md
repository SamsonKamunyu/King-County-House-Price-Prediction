# King-County-House-Price-Prediction
## Author - Samson Kamunyu

![image](https://user-images.githubusercontent.com/109947291/193143491-72b9369e-4d14-4bf1-a3de-1464ebae8ac7.png)

Creating a model that aims at predicting sale prices for houses in the King County Area.

## Overview
I work as a Junior Data Scientist at Proptech Properties Limited. I have been tasked with investigating King County House Sales dataset and draw crucial insights that will help our company improve on house sales by building a high quality model that predicts house sale prices. The company will use this information to reach potential homeowners who are looking to buy high end quality properties. To acieve the goal, we will used both simple and multiple linear regression to analyse and build a predictive model. 

## Business Understanding
Since Proptech Properties Limited is in the business of buying and selling property, our objectives for the analysis are:
- What are some of the attributes that will influence sale prices?
- Which are some measures to make in order to attract higher house sale prices in King County?

## Data Understanding
I was provided with King County House Sales dataset to work with in my analysis of the area. The data was in CSV format and had more than 20,000 data points. It had the following features as columns:
- id - unique identified for a house
- dateDate - house was sold
- pricePrice - is prediction target
- bedroomsNumber - of Bedrooms/House
- bathroomsNumber - of bathrooms/bedrooms
- sqft_livingsquare - footage of the home
- sqft_lotsquare - footage of the lot
- floorsTotal - floors (levels) in house
- waterfront - House which has a view to a waterfront
- view - Has been viewed
- condition - How good the condition is ( Overall )
- grade - overall grade given to the housing unit, based on King County grading system
- sqft_above - square footage of house apart from basement
- sqft_basement - square footage of the basement
- yr_built - Built Year
- yr_renovated - Year when house was renovated
- zipcode - zip
- lat - Latitude coordinate
- long - Longitude coordinate
- sqft_living15 - The square footage of interior housing living space for the nearest 15 neighbors
- sqft_lot15 - The square footage of the land lots of the nearest 15 neighbors

## Technologies Used
- Pandas
- Numpy
- Seaborn
- Matplotlib
- Statsmodels
- Scikit Learn

## Platforms Used
- Git
- Github
- Tableau

## Modelling
We built some models and adopted one that gave us the highest variation percentage and the lowest root squared mean error.

## Conclusion
The size of living space ranked as the highest contributor to higher prices of houses in King County. Some features such as how many times a particular house was viewed did not in any way influence the sale price.
