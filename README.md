# Wine Type and Quality Prediction

Please read Group 5 Wine Quality Report - Google Docs (1).pdf for full report. 

Jupiter notebook for full analysis:

Wine Type and Quality prediction.ipynb



## GOAL OF PROJECT:
Prepare 2 different ML models, one to predict wine type (red/ white) and another to predict wine quality from a scale of 3 to 9. 
Explore stacked classifiers to acheive best results.


## HOW TO RUN:
All ipynb files can be run using Jupiter Notebook or Google Collab.

Full Analysis Notebook - Group 5 Wine Type and Quality
Wine Brewer Widget - Wine Brewer stacked Classifiers 2

## METHOD USED:
Split the data in 70% for training and 30% for testing.

Used Imputing, MinMaxScaler, OneHotEncoder, and Pipelines when necessary.

Implemented GridSearch with 5-fold cross validation for hyperparameters tuning.

Balancing techniques for our imbalanced dataset: SMOTE (Synthetic Minority Oversampling Technique) & ADASYN (Adaptive Synthetic)

Hyperparamter Tuning for :
Decision Tree
K-Nearest Neighbors
Random Forest
Ada Boost
Gradient Boost
Support Vector
Logistic Regression

Use stacked classifiers with best models

## CONCLUSION:
The dataset was unbalanced, white wine was 75% of the dataset.
To tackle the imbalance we could have tuned the oversampling techniques further.
Data visualization helped us focus on features that are more important for wine quality
We managed to build high prediction models with 99% score for Wine Type and 98% score for Wine Quality.
The stacked classifiers consistently showed great results for the Wine Quality prediction.
More feature engineering could have been done to combine features related to acidity or density with alcohol.

I created a simple widget which can take wine chemical properties and output the wine quality.

