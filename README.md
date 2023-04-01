# Restaurant-Taxi-Analysis

The goal of this exercise is to link two longitudinal spatial datasets, to perform some descriptive analyses and visualizations, 
and to describe how you would set up a predictive model.

Dataset: NYC taxi trips on 01/15/2015 and DOHMH New York City Restaurant Inspection.

1) Link the two datasets spatially by finding restaurants that were (assumed to be) visited at the destination of a taxi ride during lunchtime or dinnertime. 
By implementing KD-Tree algorithm to find the closest match to a restaurant address within a 50m buffer (radius of 50m) around a latitude longitude point in the taxi data.

2) Create an exploratory map visualizing the linked data using Kepler.gl. Using least one feature from each of the datasets in your map

3) Performing EDA to answer the following questions
  a. How far do people travel based on different types of cuisine (“CUISINE DESCRIPTION”)? How
     does this differ based on the borough where the restaurant is located (“BORO”, one of 5 large
     NYC neighborhoods)? How does this differ by meal time?
  b. What is the average tipping rate for different types of cuisine? How does this differ by borough,
     by meal time, and by number of passengers in the taxi?

