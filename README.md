# Heart Attack Prediction using Machine Learning

## Project Overview
This project predicts the likelihood of heart attacks in young individuals in India based on various health and lifestyle features. The project uses machine learning algorithms, primarily the Random Forest Classifier, to predict the risk. Additionally, it allows for user input to predict heart attack likelihood in real-time.

## Dataset
The dataset (`heart_attack_youngsters_india.csv`) includes the following features:
- **Age**: Age of the individual
- **Gender**: Gender of the individual
- **Region**: Geographical region (Urban/Rural)
- **Smoking Status**: Smoking habits
- **Alcohol Consumption**: Alcohol intake frequency
- **Diet Type**: Type of diet (Vegetarian, Non-Vegetarian, Vegan)
- **Physical Activity Level**: Physical activity level (Low/Medium/High)
- **Blood Pressure**: Systolic/diastolic blood pressure
- **Cholesterol Levels**: Cholesterol levels in mg/dL
- **BMI**: Body Mass Index
- **Stress Level**: Stress levels (Low/Medium/High)
- **ECG Results**: Results of an ECG test
- **Family History of Heart Disease**: Whether there is a family history of heart disease
- **Heart Attack Likelihood**: Target variable indicating whether the individual is likely to have a heart attack (1 = Yes, 0 = No)

## Preprocessing
- Categorical features are encoded using Label Encoding.
- Blood pressure is split into two separate columns for systolic and diastolic readings.
- Missing values are checked, and necessary columns are cleaned.

## Data Visualization
Visualizations include:
- Histograms for numerical features to understand their distribution.
- Countplots for categorical features.
- Boxplots to identify outliers in numerical features.

## Model
A Random Forest Classifier is used to train the model on the data. The model's accuracy is evaluated, and predictions are made for the likelihood of heart attacks. The trained model is saved using `joblib` for later use.

### User Input
The program accepts user inputs for various health metrics and predicts whether the user is at high or low risk for a heart attack.


  In this tarining process i used three ways and they are Random forest,KNN and also logistic regression. This is a binary classification model .I nthis 3 models i got the same accuracy of 0.805
