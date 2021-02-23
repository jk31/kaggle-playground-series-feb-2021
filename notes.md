# Kaggle - Tabular Playground Series - Feb 2021

https://www.kaggle.com/c/tabular-playground-series-feb-2021/data

## Roadmap

### Understand the shape of the data (Histograms, box plots, etc.)

* 13 continous 
* 9 categorical
* target is continous
* train N = 300k, test N = 200k

### Data Cleaning

* no missing data

### Data Exploration

* almost no correlation between target and features
* some features correlate at about 0.6
* all continous have some variance
    * maybe Thresholding Numerical Feature Variance

### Feature Engineering

### Data Preprocessing for Model
* get dummies for cat
* try standardscaler for conti

### Models and Results
* linear regression
    * y_test = 0.8639449464826138
    * kaggle = 0.86314
    * with df = df.drop(columns=["cont5", "cont8", "cont9", "cont12", "cat4", "cat6"]) to 0.867 on y_test
* ridge
    * y_test = 0.8671933522616535
* lasso
    * y_test = 0.8883934260473165 with alpha= 0.1
* randomforest
    * without optimization: Test error: 0.8583117566205638

### Model Tuning

### Ensemble Modle Building

### Results

### Submission
* maybe use full df to final training

## Notes



