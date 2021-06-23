# Udacity_Write_DS_Blog

## Blog Post
The Medium blog post can be found here: https://andrewangeles-17598.medium.com/using-data-to-plan-your-next-boston-visit-90cc22725c8c


## Project Overview
This project was done as part of Udacity's Data Science Nanodegree Program, with the aim of getting an understanding of key aspects of the data science process: getting data, assessing data, exploring and manipulating data, using developed unitition to create and assess a model.

In the project I leverage a dataset covering Boston Airbnb listings from 2016 to 2017. The data itself is gathered from Kaggle (https://www.kaggle.com/airbnb/boston), and consists of 3 different files consisting of calendar.csv, listings.csv, and reviews.csv.

After exploring the data and modifying as needed, I then analyze the data with an end goal of developing a model to help predict the price of listings. The first area of interest focuses on the impact of seasonality on prices and inventory, the second question leverages sentiment analysis packages to analyze how positive or negative different listing reviews are and what factors may play a role. The third and final area of exploration is the impact of different features such as room type impact price, and the development of linear regression that takes varios inputs to try and predict listing price. 

## File Descriptions
Airbnb_Analysis.ipynb is the Jupyter notebook containing the code to support the initial data loads, data assessment and clean up, and the creation of different .png files and the final linear model.

** Note the individual files can be download at the link provided above, and they were ommited due to issues when commiting on git. Removing those files reduce the commit size and allowed me to commit and for that reason they are not included here.

## Libraries
On top of the standard python functions, to carry out the analysis in the notebook the following libraries are used:
- Numpy
- Pandas
- Matplotlib
- sklearn.linear_model
- sklearn.model_selection
- sklearn.metrics
- seaborn
- datetime
- decimal
- re
- pandas.tseries.offsets
- sys
- textblob
