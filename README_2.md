# Exploratory Data Analysis (EDA)

## Overview
This repository contains a Jupyter Notebook, "EDA.ipynb", which focuses on the Exploratory Data Analysis of King County Real State Data. The main purpose of this analysis is to understand the underlying patterns, relationships, anomalies, etc., in the dataset, which can provide valuable insights for our client Nicole Johnson.

## Dataset

### Source of the dataset:

**database:** postgres

**schema:** eda

**Tables:** king_county_house_details, king_county_house_sales

### Description of the columns/variables

- **id** - unique identified for a house
- **dateDate** - house was sold
- **pricePrice** - is prediction target
- **bedroomsNumber** - # of bedrooms
- **bathroomsNumber** - # of bathrooms
- **sqft_livingsquare** - footage of the home
- **sqft_lotsquare** - footage of the lot
- **floorsTotal** - floors (levels) in house
- **waterfront** - House which has a view to a waterfront
- **view** - Has been viewed
- **condition** - How good the condition is ( Overall )
- **grade** - overall grade given to the housing unit, based on King County grading system
- **sqft_above** - square footage of house apart from basement
- **sqft_basement** - square footage of the basement
- **yr_built** - Built Year
- **yr_renovated** - Year when house was renovated
- **zipcode** - zip
- **lat** - Latitude coordinate
- **long** - Longitude coordinate
- **sqft_living15** - The square footage of interior housing living space for the nearest 15 neighbors
- **sqft_lot15** - The square footage of the land lots of the nearest 15 neighbors
- **distance_to_center** - the distance from the property to the center point 


### Objective of the analysis:

The main objective of this project is to help our client Nicole Johnson to find the right fit for her in a Lively area of the city or neighborhood and in a middle price range and in the right timing (within a year)


## Requirements
This notebook requires Python, along with several Python libraries. Ensure that you have the following libraries installed to run the notebook:

altair
jupyterlab
ipywidgets
matplotlib
pandas
jupyterlab-dash
seaborn
python-dotenv
psycopg2-binary
SQLAlchemy
missingno

You can install the requirements using pip:

```
pip install -r requirements.txt
```

## Running the Notebook

Open EDA.ipynb and run the cells sequentially.

## Key Findings

- Space is expensive
"Larger houses slightly tend to be pricier in this area. Houses in neighborhoods with larger homes tend to be more expensive as well”

- Middle price range
"middle price range" consists of all the house prices between $454,625 and $739,093.75.

- Centered but not in the center. 
There are any houses available in a radius of ±1.4 km from the seattle center

- Liveness is only 1.4 km away
Within the range: 1.4 km - 3 km. Being closer to the center doesn't necessarily mean a higher price. Good opportunities in the middle price range! 

## Contact
For any queries, feel free to contact:

Name: Eric Martinez
Email: ericmartinez89@gmail.com
