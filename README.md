## Breast Cancer Risk Prediction

# About: 
- This repository uses a predictive analytics model to diagnose the risk of breast cancer amongst the individual data gathered in the dataset. Machine learning methods are applied to the data once the data exploration and pre-processing phases have been completed.

# Objective: 
- Apply machine learning fundamentals to the available dataset
- Evaluate the results achieved and justify the interpretations in the documented notebooks

# Features: 
- SVM Classifier
- Binary Classification

# Notebooks: 
1. DataClean_BCRP("Data Clean_BCRP.ipynb")
- Identify the type of data within the dataset and how to handle this information for EDA
2. ExploratoryDataAnalysis_BCRP("Exploratory Data Analysis_BCRP.ipynb")
- Assess the relationship between data variables and derive knowledge from this data exploration for the pre-processing phase 
3. DataPreprocessing_BCRP("DataPreprocessing_BCRP.ipynb")
- Identify the most predictive features of the data and begin transformation for dimensionality reduction in preparation for the SVM model
4. PredictiveModelSVM_BCRP("PredictiveModelSVM_BCRP.ipynb")
- Construct a SVM machine learning algorithm to predict the diagnosis of a breast tumour. 
- Evaluate the model using confusion matrix, receiver operating curves (ROC)
5. OptimizingSVMClassifier("OptimizingSVMClassifier_BCRP.ipynb")
- Tune the parameters of the SVM classification model