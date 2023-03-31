# Housing Project
![Kings County WA](https://www.racialequityalliance.org/wp-content/uploads/2016/10/assessors_social-1.jpg)

From: Alvaro Rodriguez, Keanan Ginell & Hera K


# Overview
For this project, we will be using multiple linear regression modeling to analyze the features used in determing house sales and prices in King's County, WA.

# Business Problem
![Kings County Map](https://images.squarespace-cdn.com/content/v1/5bf9022b5cfd79f62c905004/1609870747266-GHRDDHV2KP9W0JSUBFF4/HRAMap.jpeg)
Our team has been contracted by a real-estate company to help them improve the service they offer their customers. Specifically, we will be identifying features that impact house prices in King's County, WA. 

# Data
We used the King's County Housing Data to pull all the relevant features for determining the given price of the houses in that area. We also used an updated housing data that includes school district zones, mean household income, proximity to highest traffic,  proximity to hazardous water storage, and proximity to hazardous waste.



# Features

The main features we will be looking at are:
- Model 1: all features (including School District, Year Renovated, Zip Code)
- Model 2: all features (except zip code and year renovated)
- Model 3: all features (except year renovated categoricals)

# Results
The predicted sale price of a house and the actual sale price of the house given the above features has a correlation of about .8069, or 80.69%. 
![House Sale Price v. Prdicted Sale Price](https://github.com/drykvf/Housing-Project/blob/main/Group_plots/saleprice_predictedprice.png)

The plot shows the features ranked by their estimated impact on the house price. The Y-axis represents the percentage in mean. Waterfront would be the highest impacting feature to price given aqll the other features.
![Features v. House Price](https://github.com/drykvf/Housing-Project/blob/main/Group_plots/Features.png)

We took the waterfront feature and compared it to the median house prices, and saw that waterfront houses had a greater median price of about $400,000 than houses with no waterfronts.
![Waterfront v. Median House Price](https://github.com/drykvf/Housing-Project/blob/main/Group_plots/waterfront.png)

The plot shows the features based on school district compared to the median house prices. The school disticts 400 and 405 have the highest amount of median home prices compared to the rest of the other school districts.
![School District v. House Price](https://github.com/drykvf/Housing-Project/blob/main/Group_plots/schooldistricts_mean.png)

# Conclusions
From our analysis we have identified 20 plus features that explain 70% of the variability in house sale price.
Houses located along the waterfront have higher house prices.
Houses closer to hazardous waste storage facilities have lower house prices.
House higher Sqft living and grade have higher house prices.
School districts 400 and 405 have higher house prices.

# Next Steps
Next step we would like to revaluate our model to account for more variability and reduce the impact ourliers have on our model Looking further we want analyze individual features to obtain a broader understanding on predicted house price vs actual house price. Such as locations with affordable housing.

Additionally we would like to put together a guide showing how each feature impact house sale prices.

# For More Information
See the full analysis in the ![Jupyter Notebook](./Final_notebook.ipynb)
