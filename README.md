# Predicting Housing Sales for King County

## Purpose
  - To model the provided dataset with linear regression to predict the sale price of houses in King County, WA.
 
  
## Findings
 ### Correlation of Features
 #### Looking at the heatmap I can tell which features are correlated and seeing which features I will be keeping or dropping. 
 #### The following are showing high corrolations within the dataset:
 #### - Grade & Square foot of living space
 #### - Grade & Square foot of area minus the basement
 #### - Square foot of 15 neighbors & square foot of living space
  
  ![heatmap](https://github.com/psuero1/house-sales-project/blob/main/Visualizations/heatmap.PNG)
  
   
  
 ### Initial Model
 #### Starting at my initial model, I was able to get a Root Mean Squared Error(RSME) of 135833.92. In my model this is interpreted as having an error of $135,833.92. Additionally my R Squared is at .612. Meaning for my model it is is the percentage of the response variable variation that is explained by a linear model. So my first model can explain 61.2% of the response data around its mean. 
 
  ![initial model](https://github.com/psuero1/house-sales-project/blob/main/Visualizations/initial%20model.PNG)
  
  
 ### Final Model
 #### After going through stepwise selection, I was able to remove high P Values and was able to adjust my model a bit. The RSME increased a bit to 135837.92, so for my model $135,837.92. Although a but higher, I am comfortable with this. R Squared stayed the same at .612.  
  ![final model](https://github.com/psuero1/house-sales-project/blob/main/Visualizations/final%20model.PNG)
  
 ### Q-Q Plot
  #### On this Q-Q Plot we can see the linearity of my model.
  ![qq plot](https://github.com/psuero1/house-sales-project/blob/main/Visualizations/qq%20plot.PNG)
  
 ### Lineary & Homoscedasticity 

  ![linearity](https://github.com/psuero1/house-sales-project/blob/main/Visualizations/linearity.png)
 
 ### Conclusions and Interpretations
 #### Looking at my model, we can see a few items in the OLS on how some specific features can add a difference to housing prices: 
 #### - Square foot for house without basement increases $82.64
 #### - Square footage of basement increases $94.26
 #### - For having a second floor increases $7,131.53
 ![OLS final 1](https://github.com/psuero1/house-sales-project/blob/main/Visualizations/OLS%20final%201.PNG)
 ![OLS final 2](https://github.com/psuero1/house-sales-project/blob/main/Visualizations/OLS%20final%202.PNG)
 
 
 ### Taking a Closer Look
 #### Something that I would look further into is the zipcodes and specific locations of the houses in the data set. Of course location is important for any set housing information, having more in depth information will allow for graphs and vizualisations for real estate firms within the area. 
 

