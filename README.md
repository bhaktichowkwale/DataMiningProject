# DataMiningProject

## Overview

### EDA

We divided the tasks so that each person would perform the EDA for one year. 
Bhakti performed the EDA for the fiscal year of 2014, Amruta performed it for the fiscal year of 2015, and Kirti for 2017.

### Data cleaning
We combined the dataset using the DataCleaning notebook.

### Generation of y feature using the current features
We need to combine features to generate a new feature. This will help us use the current dataset to predict the possibilty of a vehicle obtaining a parking ticket. We think features such as color of the vehicle, location and time will help us predict the possibility of getting a ticket.

### Label Encoder
We created a smaller dataset consisting of the important features such time, location and vehicle color for classification. We then converted the strings to numerical values using the Label Encoder.

### Classifiers and Results
Initially, we decided to use SVM, KNN and Random Forest Classifiers (RFC) for classification. However, SVM wasn't converging for this dataset, so we decided to use ensemble methods such as Decision Tree, Extra Tree, ADA Boost, XG Boost, etc. The performance of these classifiers can be found in DM_Results.ipynb. 
