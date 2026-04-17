# MLOps-Experiment_Tracking-MLflow
This project demonstrates how to use MLflow for tracking machine learning experiments

## What I Did
1.Used datasets from scikit-learn - Wine dataset & Breast Cancer dataset
2.Applied Random Forest Classifier
3.Tracked experiments using MLflow
4.Ran experiments: Locally (localhost) & Remotely using DagsHub

## Features
### Manual Logging (Wine Dataset)
Logged: 
* Parameters (max_depth, n_estimators)
* Accuracy metric
* Confusion matrix (as artifact)
* Model
* Source code file
### Autolog + Hyperparameter Tuning (Breast Cancer Dataset)
* Used mlflow.autolog()
* Applied GridSearchCV for hyperparameter tuning
* MLflow automatically tracked:
* All runs
* Parameters
* Metrics
* Models
Also logged: Best parameters, Best accuracy, Training & testing datasets

## MLflow Tracking
### Local
* Tracking URI: http://127.0.0.1:5000
* Run UI using: mlflow ui
 
### Remote (DagsHub)
* Connected MLflow to DagsHub
* Stored experiments online
* Helps in collaboration and tracking
 
### Artifacts Logged
* Confusion Matrix plot
* Model files
* Source code
* Training & testing datasets

## Tech Stack
* Python
* Scikit-learn
* MLflow
* DagsHub
