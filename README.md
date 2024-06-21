# Machine-Learning-Module
Here on behalf of machine learning project we are dealing with these following topics  such as Outlier detection,Hypothesis Testing,Data Preprocessing,Regression,Cluster and Classification

#Outlier Detection
In this project we are analysing the property prices available in the city of banglore.For this we are using outlier detection and using house_price.csv.Here,we examined price per square feet and finding outliers using following methods:
### mean function
### percentile method
### interquartile range method
### normal distribution
### Z-score method
Followed by creating visual analysis of  the data using box plots, histograms, correlation heatmaps, and scatter plots in above methods.
First of all we loaded the dataset and checked out if there is any null values.This is done as a part of preprocessing.We then detected outliers in the "price per square feet  column" by applying the box plots and histograms.aAfter finding outliers the very next step is to remove those outliers ,For that we used mean function, percentile method, interquartile range method, normal distribution, and Z-score method.We then also Plotted box plots for all numerical columns to visualize outliers.Plotted box plots for all numerical columns to visualize outliers.After that we Checked the normality of the "price per square feet column" using a histogram.Later on Calculated the correlation between numerical columns and plotted a heatmap.Finally,Created scatter plots between variables to check their correlation.

# Hypothesis Testing
In this project, we perform hypothesis testing  to analyze claims made in two different scenarios. Hypothesis testing is a statistical method used to make inferences about population parameters based on sample data.
## Task 1: Child Psychologist's Claim
### Claim:
A child psychologist asserts that the average time working mothers spend talking to their children is at least 11 minutes per day.
### Sample:
A random sample of 1000 working mothers was selected, revealing an average time of 11.5 minutes spent talking to children per day.
### Population Standard Deviation:  
Previous research suggests a population standard deviation of 2.3 minutes.
### Hypothesis Test: 
A hypothesis test was conducted with a significance level (alpha) of 0.05 to ascertain if there is sufficient evidence to support the psychologist's claim.
### Choosing Method:
Since we have a sample size of 1000, which exceeds 30, and we possess information about the sample mean, standard deviation, and aim to compare the sample mean to a population value, a "Z-test" is appropriate.

The calculated z-score significantly exceeds the critical value .This leads  to the rejection of the null hypothesis.Hence, there is an evidence to summarize that working mothers spend more than 11 minutes per day talking to their children.

# Task 2: Coffee Shop's Claim
### Claim:
A coffee shop asserts that their average wait time for customers is less than 5 minutes.
### Sample: 
A sample of 40 customers was observed, yielding an average wait time of 4.6 minutes with a standard deviation of 0.8 minutes.
### Hypothesis Test: 
A hypothesis test was conducted at a significance level of 0.05 to determine if there is adequate evidence to support the coffee shop's claim.
### Choosing Method:
 Since the sample size is small than 30 and the population standard deviation is unknown "t-test" is appropriate for this scenario.
 
 The calculated t-value  is lower than the critical t-value this leads to the failure to accept the null hypothesis. This indicates sufficient evidence to support the claim that the average wait time for customers is less than 5 minutes at a significance level of 0.05.

# DATA PREPROCESSING

https://drive.google.com/drive/folders/18rpobr58R_e8zrp26Nk1ievYmhHB7_kT?usp=sharing

This project is mainly dealing with data preprocessing to enhance the quality and usability of datasets for machine learning applications. By addressing issues like missing values, outliers, and inconsistent formatting, we are trying to improve data integrity and analysis outcomes.The main steps in this project are:
#### Data Exploration:
Understand dataset structure, identify unique values, and perform basic statistical analysis
#### Data Cleaning:
Handle missing values, remove duplicates, and address outliers
####Data Analysis:
Filter and visualize data based on specific criteria.
#### Data Encoding:
Convert categorical variables into numerical representations.
#### Feature Scaling:
Standardize or normalize feature values for improved model performance.
 
