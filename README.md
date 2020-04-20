# Background

I am a data scientist at Blackwell Electronics, an electronics retailer. I will use machine learning methods to predict customer brand preference, predict sales volume, and run a market-basket analysis to find assocations between products.

# File Summaries

## 1. TaskDescription.md
Email from CTO at Blackwell Electronics summarizing project.

## 2. CustomerBrandPreference
Folder containing all files for predicting customer brand preference. 

### 2.1 ProjectBackground.md
Email from CTO explaining problem, task, and data. We ran a survey to see which computer brand our customers prefer. Some of the survey results came back incomplete. I will build a model based on the complete survey results to predict the brand preference for the customers who did not fully complete the survey. 

### 2.2 Data
Contains marketing survey results, marketing survey key, and results from the incomplete surveys.  

### 2.3 PreviousProgressInR_withCaret
I had initially started this project using R but finished it in Python. This folder contains the R code (in .rmd) using R's  CARET package.  

### 2.4 python_CompleteAnalysis
Full analysis and model building in Python. 

#### 2.4.1 ExploratoryDataAnalysis.ipynb
Preprocess and visualize data.

#### 2.4.2 ModelBuilding.ipynb
Build and run model to predict brand preference. 

### 2.5 Customer Brand Preferences Report.pdf
Summarize relationship between variables, provide results and model performance metrics.

### 2.6 predictionResults.csv
Prediction results from model for customers in the incomplete survey. This file is sent to marketing department.

## 3. Sales Volume Predictions
Folder containing all files for predicting product sales.

### 3.1 Data
Contains data on existing products and their attributes, new products and their attributes, and preprocessed new products data used on model. 

### 3.2 analysis_in_R_incomplete
I had worked on this project using RapidMinor Studio, R, and eventually Python. This folder contains code from my analysis in R (.rmd) and notes on model performance results from RapidMiner in pdf. 

### 3.3 CompleteAnalysis.ipynb
Contains exploratory data analysis and model building in Python. 

### 3.4 Results
groundTruth.csv shows actual sales volume (grouthTruth) from the existing attributes data and the predicted sales volume from my model. newProductPredictions.csv shows the predicted sales volume from applying the model on the new attributes data set. 

## 4 DiscoverAssicationsBetweenProducts
Folder containing all files for market basket analysis.

### 4.1 ProjectBackground.md
Blackwell is considering acquiring a startup and needs to better understand the startup's clientele.

### 4.2 Data
ElectronidexTransactions2017.csv contains Electronidex's transactions in 'basket' or 'transactional' data format.
ProductList.csv lists the names of the products that Electronidex sells. 

### 4.3 R Code
Analysis_Notebook.Rmd contains analysis in R. Association Between Products.pdf contains the same analysis but in PDF for easier rendering. 

### 4.4 Report for Market Basket Analysis.pdf
Presents top and least selling items, interesting relationship between items, and business recommendations. 

