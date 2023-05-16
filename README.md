# Pore Pressure Prediction Model for Oil and Gas Exploration and Production
==============================
                                                                    
This repository contains a machine learning model for predicting pore pressure in the context of oil and gas exploration and production. Pore pressure, which represents the pressure exerted by fluids within rock formations, is a crucial parameter in drilling operations, reservoir characterization, and wellbore stability analysis.

The aim of this work is to leverage the power of machine learning techniques to accurately estimate pore pressure values, enabling better decision-making in drilling operations and reducing potential risks. The model is trained using a dataset comprising various geophysical and geological features, such as seismic attributes, well logs, lithology, and other relevant information.

## Objective
The goal of this project is to develop an accurate and reliable machine learning model that can estimate pore pressure values based on various geophysical and geological features. By leveraging advanced data analysis techniques, this model aims to enhance decision-making in drilling operations, optimize reservoir management, and reduce risks associated with wellbore stability.

## Requirements
The following Python packages are required to run this model:

1. Pycaret
2. pandas
3. numpy
4. scikit-learn
5. joblib
6. flask
7. EvalML
8. Matplotlib

You can Install the necessary dependencies ```pip install -r requirements.txt``` in the command line.

## Usage

**Clone this repository to your local machine.**
```bash
https://github.com/obinopaul/Pore-Pressure-Prediction-for-Oil-and-Gas.git                                       
```

## Models and Results
Three different machine learning models were developed to predict pore pressure:
1. Pycaret: Utilizing the Pycaret library, an automated machine learning framework, a model was trained and evaluated on the dataset. The best-performing model (ExtraTreesRegressor) achieved an R2 score of 97.3%.
2. EvalML: The EvalML library was employed to build a machine learning pipeline for pore pressure prediction. The pipeline incorporated data preprocessing, feature engineering, and model training. The best model (XGBoost Regressor) achieved an R2 score of 95.4%.
3. ExtraTreesRegressor: with insights from the Pycaret model, an ExtraTreesRegressor algorithm (from the Sklearn Library) was used to develop a custom machine learning model. The model was fine-tuned and evaluated, resulting in an R2 score of 97.4%, a little higher than the PyCaret model


"#Pore_Pressure_Prediction_for_Oil_and_Gas" 