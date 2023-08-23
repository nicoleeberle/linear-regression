# Linear Regression Analysis: Distance to nearest Syringe Services Program 
Here you can see a regression modeling project that I completed to estimate a counties distance to the nearest Syringe Services Program (SSP) using linear regression.
This project outlines a modeling thought process that can be used on many different types of datasets and to answer a wide variety of questions. 

The analysis walks through completing summary statistics and visualizing the date before modeling in order to understand what type of data you are working with.
As a result of the exploratory data analysis, any neccessary cleaning and transformations are completed. 
When the data is ready to be modeled, models are run and refined based on variable significance and by checking the model assumptions to ensure there is no multicollinearity, that observations are independent, and that residuals are normally distributed and have homoscedasticity.
This analysis also explores interaction variables to see if two variables combined have an effect the outcome that is more than their individual effect. 

# Files
The following files are available to download:
1. PDF: Final write up of project including all code, visuals and analysis. This is all you need to see the full project
2. Code: RStudio code file. This allows you to re-run the analysis on your own.
3. Data: The two CSV files used to build the dataset. This allows you to re-run the analysis on your own. 

# Project Topic
This dataset examines the distance varying counties are from the nearest Syringe Services Program (SSP). 
The dataset provides the HIV Prevalence, Opioid Rx Rate, and Percentage Uninsured for each county, along with county categorical information such as 
state, region and metro/non-metro. The focus of the analysis was to predict the distance to the nearest Syringe Services Program based on county characteristics.

# Conclusion
Overall, this is not a very strong model and definitely still has room for improvement, despite the many variations tried. 
Additional data cleaning may be necessary, along with comparing the model to a version created without the observations that have high leverage.
