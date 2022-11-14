# Heart Disease Prediction

This notebook contains an analysis of a heart disease data set, builds several types of classification models and evaluates them. The data contains 14 columns which show different characteristics of the songs.

## Data set

The data set used is uploaded to this folder and was originally taken from [this page](https://archive.ics.uci.edu/ml/datasets/Heart+Disease)

|    | Variable   | Explanation                                                |
|---:|:-----------|:-----------------------------------------------------------|
|  0 | Age      | Age in years                                      |
|  1 | Sex     | 0 = female, 1 = male|
|  2 | Chest pain type  | 1: typical angina; 2: atypical angina; 3: non-anginal pain; 4: asymptomatic|
|  3 | BP       | Resting blood pressure                    |
|  4 | Cholesterol        | Serum cholesterol in mg/dl                    |
|  5 | FBS over 120       | Fasting blood sugar > 120 mg/dl: 0 = false, 1 = true  |
|  6 | EKG results       | Resting electrocardiographic results: 0 = normal; 1 = abnormality; 2 = hypertrophy|
|  7 | Max HR         | Maximum heart rate achieved  |
|  8 | Exercise angina       | exercise-induced angina: 1 = yes; 0 = no  |
|  9 | ST depression        | ST depression induced by exercise |
| 10 | Slope of ST        | The slope of the peak exercise ST segment: 1: upsloping; 2: flat; 3: downsloping   |
| 11 | Number of vessels fluro      | Number of major vessels (0-3) colored by fluoroscopy|
| 12 | Thallium       | 3 = normal; 6 = fixed defect; 7 = reversable defect |
| 13 | Heart Disease        | Diagnosis of heart disease|

## Objectives

The notebook has a goal of building classification models and covering the following topics:

* Perform an analysis of the data
* View the data using visualizations
* Build classification models:
  1. K-Nearest Neighbor
  2. Logistic Regression
  3. Support Vector Machine
  4. Decision Tree
* Evaluate the performance of the models and decide on the best one

## Tools used

This Jupyter notebook analysis and modeling is performed in Python with the help of Scikit-learn library.
