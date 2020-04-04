# Data analysis project
##Group: Anders&Frederik

Our project is titled **The real number of Corona cases in Denmark** and is about trying to estimate the "dark" number or underreported cases of Corona Virus in Denmark. We first give an overview of the sitaution in Denmark; graphing the Corona cases, deaths, recovered, death rate and recovered rate, then, we use a simple exponential growth model to estimate the underreported number of Corona cases in Denmark.

The **results** of the project can be seen from running [dataproject.ipynb](dataproject.ipynb).

This **loades the datasets**:
**covid_19_data.xlsx**:

We use data from John Hopkins University originating from Statens Serum Institut. 

The data can be downloaded from this Kaggle:
https://www.kaggle.com/sudalairajkumar/novel-corona-virus-2019-dataset#covid_19_data.csv 
We have converted the csv-file to a xlsx-file before uploading it to our repository. 

The methods used to estimate the underreported cases are inspired by the website:
https://www.python-course.eu/corona_cases_estimation.php
