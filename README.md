# Predicting Customer Preferences

Blackwell Electronics is a successful consumer electronics retailer with both bricks & mortar stores in the southeastern United States and an eCommerce site. They have recently begun to leverage the data collected from online and in-store transactions to gain insight into their customers' purchasing behavior. My job is to extend their application of data mining methods to develop predictive models through  R and Python.

I will use machine learning methods to predict which brand of computer products Blackwell customers prefer based on customer demographics collected from a marketing survey, and then I will go on to determine associations between products that will be used to drive sales-oriented initiatives such as recommender systems like the ones used by Amazon and other eCommerce sites. Finally, I will present to management, explaining my insights and suggestions for data mining process improvements.

Source: University of Texas Data Analytics Certificate Program

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


## 3. SalesVolumePredictions
Folder containing all files for predicting sales volume. 

### 3.1 PreviousProgressInR            `                        ````````````````````````````````````````````````````````````````````
I had initially started this project using R but finished it in Python. This folder contains the R code (in .rmd) using R's  CARET package.


## 4. DiscoverAssicationsBetweenProducts	
Folder containing R code of analysis in PDF format for better rendering.

## 5. Images
Folder containing visualizations created during analysis. 

## 6. FinalReportForClient.pdf
Written report containing results, caveats and methodology. 
