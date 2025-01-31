## UCB Data Analysis Bootcamp Project 4: Improving Parkinson’s Diagnosis with Artificial Intelligence 

## Objective
In this project, we intend to use machine learning to better understand the factors that most contribute to a Parkinson's diagnosis and create a model that helps healthcare professionals determine if a patient should be diagnosed with Parkinson's disease. The dataset contains comprehensive patient data such as health factors, medical/familial history, symptoms, and cognitive/functional assessments as well as data indicating the patient's final diagnosis. 

## Results
Multiple types of models were initially analyzed, including logistic regression, KNN, decision tree, and a neural network. The decision tree indicated that the most significant determining factor in a patient's diagnosis of Parkinson's disease is the presence of tremors, with rigidity and bradykinesia, or slow actions, also acting as determining factors. Ultimately the neural network was most accurate in predicting a Parkinson's diagnosis.
A neural network model was compiled, trained, and analyzed using the comprehensive patient data as is with a resulting accuracy of 0.8216, however, a significant loss of 0.4627 was also present. With optimization of the model through binning of data, specifically the diagnostic testing data, the model achieved a consistent accuracy above 0.8823 and a reduced loss of 0.3852. An additional model was created using only the patient's health data, medical/familial history, and symptoms, without the scores provided by the diagnostic tests. This was done in an effort to investigate how the patient's health data alone influenced their diagnosis. This model resulted in an accuracy of 0.6679, however a large loss of 0.7380 was also identified. 


## Team Members
- Chris Alzuires, Visualizations Specialist
- Paige Andrews, Data & Parkinson's Specialist
- Rowan Clark, Machine Learning Specialist
- Shalini Pampati, Database & Visualization Specialist
- Diya Sadekar, Data Specialist
- Tugce Terizioglu, Project Manager


## Repository Contents
This repository contains all the code files and our presentation slides.


## Subfolders
- Data Cleaning: Contains the .ipynb files and .csv files
- Data Frame: contains the .ipynbs and .png files used to create data frames and visualizations.
- Machine Learning Models: contains .ipynb files used to create multiple different models, including logistic regression, decision tree, KNN, and the neural network in both the initial and optimized forms.
- Resources: original .csv file of data set from Kaggle.
- Screenshots: includes pictures of code, visualizations, etc. that are included in the presentation.
- SQlite: Contains the .db file used to retrieve data through SQLalchemy.


## Tools and Technologies used:
- Pandas: utilized for DataFrame creation, data manipulation, and analysis.
- Scikit-Learn: utilized in data preprocessing to train machine learning model.
- SQLalchemy: utilized to retrieve data.
- Tensorflow: utilized to compile, train, and evaluate neural network models.
- Matplotlib: utilized to create visualizations of data.
- Seaborn: utilized to create complex visualizations of data. 

  
## Data Sources
- Kaggle: https://www.kaggle.com/datasets/rabieelkharoua/parkinsons-disease-dataset-analysis








