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


