# PARKINSONS_DISEASE_PREDICTION

## OVERVIEW
Parkinson's disease is a progressive disorder that affects the nervous system and the parts of the body controlled by the nerves. ymptoms start slowly. The first symptom may be a barely noticeable tremor in just one hand. Tremors are common, but the disorder may also cause stiffness or slowing of movement.Diabetes can cause blood sugar levels to rise if it is not continuously and carefully managed, which raises the chance of severe side effects like heart attack and stroke. I, therefore, choose to forecast using Python machine learning algorithms inorder to predict the disease accurately.

## OBJECTIVE
The main aim of the project is to predict parkinsons disease  via three different supervised machine learning methods including: SVM, Logistic regression and the MLP Classifier . This project also aims to propose an effective technique for earlier detection of the parkinsons disease so that a person can avoid the serious stage/conditon of the disease .

## LIBRARIES USED
A Python library is a collection of related modules. It contains bundles of code that can be used repeatedly in different programs. It makes Python Programming simpler and convenient for the programmer. As we don’t need to write the same code again and again for different programs. Python libraries play a very vital role in fields of Machine Learning, Data Science, Data Visualization, etc.Python libraries that are used in the project are: • Pandas • gradio • Numpy • Matplotlib

## MODULES DESCRIPTION
Dataset Collection:
This module includes data collection and understanding the data to study the patterns and trends which helps inprediction and evaluating theresults.Dataset description is given belowThis Diabetes dataset contains 800 records and 10 attributes. Table 1. Dataset Information Attributes Type Number of Pregnancies N Glucose Level N Blood Pressure N Skin Thickness(mm) N Insulin N BMI N Age N

## Data Pre-processing:
This phase of model handles inconsistent data in order to get more accurate and precise results. This dataset containsmissing values. So we imputed missing values for few selected attributes like Glucose level, Blood Pressure, SkinThickness, BMI and Age because these attributes cannot have values zero. Then we scale the dataset to normalizeall values.

## Clustering:
In this phase, we have implemented K-means clustering on the dataset to classify each patient into either a diabeticor non-diabetic class. Before performing K-means clustering, highly correlated attributes were found which were,Glucose and Age. K-means clustering was performed on these two attributes. After implementation of this clustering we got class labels (0 or 1) for each of our record.

## Model Building:
This is most important phase which includes model building for prediction of diabetes. In this we have implementedmachine learning algorithms for diabetes prediction. These algorithms include Support Vector Classifier,Logistic Regression, K-Nearest Neighbour, Gaussian Naïve Bayes,Bagging algorithm, Gradient Boost Classifier.In this,I have just implemented the MLP Classifier.

## Evaluation:
This is the final step of prediction model. Here, we evaluate the prediction results using various evaluation metricslike classification accuracy, confusion matrix and f1-score.Classification Accuracy- It is the ratio of number of correct predictions to the total number of input samples.


# HAPPY LEARNING
# HAPPY CODING
