# Final-Project-Statistical-Modelling-with-Python

# Project/Goals

(1) To gather data from different sources using the API Keys.

(2) Join the data obtained and create a data base in SQlite

(3) Create tables for data and arrive at a final result for further analysis.

(4) Perform an EDA

(5) Deveop a statistiacl model to identify the correlation and prediction between dependent and independent variable.
              
# Process
(1) Connecting to CityBikes API

(2) Connecting to Foursquare and Yelp APIs

(3) Joining Data

(4) Building a Model

 Results

 Created a Linear Regression Model between 'Bikes Available' (dependent variable) and ['Distance', 'Rating'] (independent variables)



# Interpretation of the model
(1) Model Fit: Adj. R-squared is very low, i.e it only (0.2)% of variance in Bikes Available is explained by the independent variable

(2) if we remove rating from independent variable and fit the model it shows that the distance doesn't explaind the variance of bikes available at all.

(3) 0.2% variance is for rating only : it does have effect on Bikes Avaialble(but very little)

(4) we can conclude that ther model is very poor and we will need more data to further check relations between variables


Even after removing Rating(indepedent variable) and review_counts(independent variable), there is no/little effect of distance on Bikes Available for each Sations

Note: All the steps are highlighted in the files under the folders data, images and notebooks.

# Challenges 

Gathering Data from differenet APIs:
Different APIs option available to gather data from:
(1) Foursquare:
(1) Need to provide precise parameters for POI(points of interest)
(2) Data mixed with null values
(3) Can make multiple  requests
(2)Yelp:
(1) Detailed response with just including interested point in query
(2) More precise data with no nulls or duplicated values
(3) Very Limited API requests (Have to write complete code as to not run out of request)

                                
  # Future Goals
I worked on the point of interest variables and identified that they have very low influence on the dependent varable.
The next thing I would focus on other stats models to identify the variable that inluences dependent variable.
