# Stroke_Prediction_ML_Models - Stroke Detection Using Imbalanced Learning Techniques

# Introduction

1. Problem definition: Detecting risk of stroke occurrence in patients using health indicators
2. Project objective: Build a classification model to predict stroke risk using patient health data

# Data

1. Dataset has 43,400 samples for training and 18,601 for testing
2. 12 features collected for each patient sample
      Demographics (age, gender)
      Health measurements (glucose levels, BMI)
      Lifestyle factors (smoking status)
      Medical history (heart disease, hypertension)
3. Target variable is occurrence of stroke

# Modeling Approach

1. Naive Bayes classifier
  Accuracy: 97.4%
  High recall in predicting no stroke; lower for predicting stroke occurrence
  
2. Decision Tree
  Accuracy: 97.9%
  High overall accuracy but low in predicting stroke
  
3. Random Forest
  Accuracy: 98.0%
  Perfect no stroke recall; failed to predict stroke occurrences
  
4. Neural Network
  Accuracy: 98.2%
  Performance similar to random forest
  
# Conclusions

1. Random forest model had best balance of accuracy
2. Models predict absence of stroke well, but predicting occurrences is difficult
3. Could help identify patients not at risk, further screening of at-risk groups
4. Future work: collect more patient data of under-represented stroke cases
