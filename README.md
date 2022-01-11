# Overview of Seattle_Airbnb
This repository contains code used for analysis of publicly available Airbnb data
The data are in CSV format and the code used to generate the analysis is in Jupyter notobooks (written in Python)

The analysis is published at: https://medium.com/@spilios.tzouras/leverage-data-and-analytics-to-optimize-business-and-services-to-airbnb-tenants-the-seattle-case-d06a85fe2119


# Libraries used
- pandas # for data manipulation
- os # for data manipulation
- numpy # for data manipulation
- time # for adding time delays
- from sklearn.cluster import KMeans # for k-means clustering
- plotly # for making graphs
- matplotlib.pyplot # for data visualization
- from plotly import graph_objs # for data visualization

# Motivation
The aim of the code hosted in this repo is to illustrate how could data and analytics be used to optimize services for Airbnb tenants. The dataset used is the Airbnb listed properties in Seattle

# Files
- Seattle_AirBnB Data Exploration - Part 1vSrd.ipynb: Contains the python code used to clean the data and make them ready for analysis
- Seattle_AirBnB Data Analysis - Part 2vSrd.ipynb: Contains the python code used to analyse the data and make inferences 
- map1: Is a png file of the Seattle map in the right dimensions for ploting the coordinates of the Airbnb properties in the area. It is needed when running "Seattle_AirBnB Data Analysis - Part 2vSrd.ipynb"
- calendar.csv.zip : Airbnb data with the status of the properties within a time interval
- listings.csv.zip: Airbnb data describing the characteristics of the properties 
- reviews.csv.zip: Airbnb data with reviews by tenants 


# Results
The output of the analysis shows that mainstream machine learning techniques (such as clustering and non-linear regression) can reveal patterns that exist in the data, these inferences can be used to streamline decision making
