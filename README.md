# Credit Card Default Capstone Project

#### This repository contains the code and documentation for my capstone project on the Credit Card Default dataset. The analysis has been fully conducted with #### Python language, exploiting several machine learning and statistical frameworks available such as scikit-learn, numpy, pandas, imblearn together with other data visualization libraries (matplotlib and seaborn). 
#### In this study we aim to exploit some supervised machine learning algorithms to identify the key drivers that determine the likelihood of credit card default. The goal is to build an automated model for both identifying the key factors, and predicting a credit card default based on the information about the client and historical transactions. The algorithms used to build the models in particular, Decision Tree, Logistic Regression, and Random Forest have been applied

## Dataset

#### The dataset used in this study is the Default of credit card clients from the UCI machine learning repository, available at the following link. It consists of #### 30000 observations that represent distinct credit card clients. Each observation has 24 attributes that contain information on default payments, demographic #### factors, credit data, history of payment, and bill statements of credit card clients in Taiwan from April 2005 to September 2005. As can be seen, a number of #### 6.636 out of 30.000 (or 22.1%) of clients will default next month (i.e. has category 1). In order to get a first look at how data is presented, some #### observations of the dataset are shown in the table below. No missing feature is recorded for any of the 30.000 samples.

## Exploratory Data Analysis

#### The main aim of the data is to discriminate clients that are predicted to credit card default the next month, according to the default.payment.next.month column which is set to “0” for non-defaulters and “1” for defaulters. Thus, it is a binary classification problem on a relatively unbalanced dataset

#### Data Loading and Initial Exploration: I loaded the dataset into a Jupyter Notebook and examined its structure, dimensions, and basic statistics using descriptive functions.

#### Data Cleaning and Preprocessing: I assessed the quality of the data, handled missing values, and checked for duplicates. Additionally, I transformed and standardized variables as necessary.

#### Univariate Analysis: I explored each variable individually to understand its distribution, range, and outliers. This involved generating summary statistics, histograms, and box plots.

#### Bivariate Analysis: I analyzed the relationships between pairs of variables to identify potential correlations or dependencies. I used techniques such as scatter plots, correlation matrices, and grouped analysis to uncover insights.

#### Multivariate Analysis: Building upon the bivariate analysis, I investigated relationships among multiple variables simultaneously using correlation matrix. This allowed me to uncover more complex patterns and interactions within the dataset.

#### Visualization: Throughout the EDA process, I utilized various data visualization techniques, including bar charts, box plots, density plots. These visualizations enhanced the understanding of the dataset and made it easier to communicate findings.

#### Boxplots for numeric attributes

#### Min max scaling of numeric attributes

#### Standard scaling of numeric attributes

#### Due to the lack of domain knowledge and the very high number of identifiable outliers, no samples have been discarded as outliers.

#### One hot encoding for categorical variables

#### Feature Importance using Extra tree classifers

## Classification Algorithms : 
#### Decision Tree
#### Random Forest
#### Logistic Regression

## Evaluation Methods :
#### K-Fold Cross validation
#### Random Split method

## Discussion :
#### 


### Repository Structure

#### credit_card_default.csv: The dataset file containing credit card client data.

#### Capstone Project.ipynb: Jupyter Notebook containing the code and detailed analysis of the EDA process.

#### README.md: This file, providing an overview of the project and repository.

#### Abstract 

#### Literature Review
