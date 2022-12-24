# Energy Price Prediction with Amazon Sagemaker XGBoost

## Description

This is a project of predicting hourly energy (electricity) price using Amazon Sagemaker XGBoost.

The dataset is collected from https://www.kaggle.com/datasets/nicholasjhana/energy-consumption-generation-prices-and-weather. Both the energy and weather feature datasets are provided, but only the energy dataset is used in the project. 

The purpose of this project is to demonstrate an end-to-end pipeline of a machine learning model and show how the model is deployed on the aws cloud platform. 

The file has two notebooks. The first one is about data processing and runs on Google colab to save billing on aws; the second one demonstrates model building, training and deployment. 

## Data Science Lifecycle from IBM Data Science Program

![download](https://user-images.githubusercontent.com/81448993/209453475-fd0c1312-afad-4838-a7e3-ea531ece7654.png)


## References
1. https://github.com/aws/amazon-sagemaker-examples/blob/main/hyperparameter_tuning/xgboost_direct_marketing/hpo_xgboost_direct_marketing_sagemaker_python_sdk.ipynb
2. https://www.youtube.com/watch?v=vV12dGe_Fho
3. https://www.youtube.com/watch?v=XSsnPtHRZ6A&list=PLZoTAELRMXVONh5mHrXowH6-dgyWoC_Ew&index=10
