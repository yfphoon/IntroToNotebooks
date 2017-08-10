## Introduction to Notebooks for SPSS Professionals Lab
This repository contains data and analytic assets for the Lab. The iPython Notebook is designed to run on 
<a href="https://datascience.ibm.com" target="_blank">IBM Data Science Experience</a> and analyzes the churn.csv and customer.csv data sets.

### Getting Started
- Create a **Project** in DSX Cloud and name it *IntroToNotebooks*
- Within the *IntroToNotebooks* project, **add a Notebook** and choose to import it from this **URL**: 
  https://github.com/yfphoon/IntroToNotebooks/blob/master/Predict%20Customer%20Churn%20-%20Build%20Model.ipynb
- Work through the "*Predict Customer Churn - Build Model*" notebook

#### (Optional) Access data in flat files
- Download ![churn.csv](data/churn.csv?raw=true) and ![customer.csv](data/customer.csv?raw=true), and add them into the *IntroToNotebooks* project
- Create a duplicate of the "*Predict Customer Churn - Build Model*" notebook
- Edit the "*Predict Customer Churn - Build Model copy 1*" notebook to read the data from the flat files

#### (Optional) Build a LogisticRegression model
- Create a duplicate of the "*Predict Customer Churn - Build Model*" notebook
- Edit the "*Predict Customer Churn - Build Model copy 2*" notebook
- In "*Step 6: Build the Spark pipeline and the Random Forest model*", edit the code to build a LogisticRegression Model
