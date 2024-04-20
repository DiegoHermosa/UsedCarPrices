# What drives the price of a car?
**OVERVIEW**

In this application, we will explore a dataset from kaggle. The original dataset contained information on 3 million used cars. The provided dataset contains information on 426K cars to ensure speed of processing.  The goal is to understand what factors make a car more or less expensive.  As a result of this analysis, wer'e going to provide clear recommendations to the client -- a used car dealership -- as to what consumers value in a used car.

To frame the task, throughout this practical applications we will refer back to a standard process in industry for data projects called CRISP-DM. This process provides a framework for working through a data problem. 
Next sections will show the CRISP-DM Steps applied to mentioned topic

### Business Understanding
In order to be able to identify and understand what are the key drivers for used car prices, we are going to work on the data of used car business which was previously collected and provided to us by a dataset (CVS Format). We are going to apply the data analysis techniques for getting the knowledge about the data atttributes and use the Machine Learning tools for the processing of the data.
The dataset contains different attributes of the sale of used cars like: the price, the location, color and engine features and many others.

### Data Understanding
1. Explore the dataset attributes to know about the data types
2. Plot the data to see their distribution
3. Identify missing data:
  - What attributes don't contain data.
  - Determine the amount of records per attribute with that condition.
  - Define how to deal with missing values: drop the records, replace the value, drop the column
4. Detect and remove the outliers for price attribute
5. Identify what are the categorical and ordinal features:
  - Identity unique values per attribute.
  - Apply the proper encoder so they can be used in the regression model.
6. Identify what attributes are not needed and remove them from dataset
7. Run the correlation to the target so we can identify what features have a strong positive correlation.

### Data Preparation
See the prompt_II.ipynb, there in the section Data Preparation was don

