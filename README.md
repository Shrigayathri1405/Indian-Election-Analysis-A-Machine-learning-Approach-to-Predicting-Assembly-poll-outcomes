# Indian-Election-Analysis-A-Machine-learning-Approach-to-Predicting-Assembly-poll-outcomes
## Dataset Overview 
Source:IndiaDataPortal.com
Size:1,00,000+ candidate-level records
Attributes:Candidate info,votes,age,gender,party constituency,turnout,margins etc..
## Machine Learning Problem Statement 
Predict whether a candidate will win or lose an election based on the features present in the dataset
Target Variable:is_winner
Variable Type:Binary Classification
## Technologies and Tools used 
Python(Libraries such as Pandas,NumPy,Seaborn and Matplotlib)
ML Models:Naive Bayes,K-Nearest Neighbors,Random Forest Classifier,LightGBM,XGBoost,CatBoost
Model Evaluation:Accuracy,Precision,Recall,F1 score,Confusion matric,ROC curve
## ML Highlights 
| Model            | Accuracy 

| **CatBoost**     | 94.8%    
| **XGBoost**      | 93.5%    
| **RandomForest** | 94.6%    
| **KNN**          | 94.6%   
| **Naive Bayes**  | 86.4%
CatBoost and Random Forest performed best in terms of F1 score 
## Insights  Extracted 
Most winning candidaes are aged between 40-60
Gender predicted using name via NLP 
Vote margin and turnout percentage are  strongest predictors of winning
Certain states show consistent high turnout percentage and margin patterns
## Files in the Repository 
Election_Analysis.ipynb - Notebook with all analysis 

Gender_Data.csv- Names and gender for training

missing_sex_filled.csv - Dataset after model deployment

assembly-elections-data-at-candidate-level.csv-Original raw dataset
## Author 
Built by Shri Gayathri S
