# Google-Play-Store-Apps-Project
## Context
The Play Store apps data has enormous potential to drive app-making businesses to success. Actionable insights can be drawn for developers to work on and capture the Android market!

## Data Features
Each app (row) has values for catergory, rating, size, price, genres, and more.

## Content
This Github repository contains two Python notebooks. 
* [Google Play Store Apps - Data Preprocessing](https://github.com/baolingz/Google-Play-Store-Apps-Project/blob/master/google-play-store-apps-data-preprocessing.ipynb) 
* [Google Play Store Apps - EDA](https://github.com/baolingz/Google-Play-Store-Apps-Project/blob/master/google-play-store-apps-EDA.ipynb)

In the first notebook, I removed irrelevant columns and outliers. Plus, I filled missing value using mean imputation technique. In addition, I converted all categorical variables-except category, genre and type-into numerical values. Lastly, I log-scale number of reviews and installs.

In the second notebook, I have broken down all Google Play Store apps by Category and drawn boxplot charts to generate insights regarding their ratings, sizes, prices, number of reviews and downloads and etc. Besides, I also conducted correlation analysis between all parameters for 32 categories, including family, game, business, medical and etc. Comments was added under each charts and key takeaways can be seen at the end of the page.

A third notebook will be added soon, including the following analysis: 

* Since I've observed totally different correlation patterm between paid and free apps, I am interested to build a classfification model to determine whether a developer can make a paid app and acheive considerable downloads with given parameters, including app's category, name's length, size and rating.     
* Before doing so, I would like to build a regression model to predict the number of downloads based on all other app's parameters.
