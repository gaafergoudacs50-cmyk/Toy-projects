# Kidney Disease Classification

## Overview

This project is an end-to-end Deep Learning application that classifies
kidney CT scan images into disease categories using Convolutional Neural
Networks (CNNs) and Transfer Learning.

The project follows modern MLOps practices, including data versioning
with DVC, experiment tracking using MLflow, model training, deployment,
and CI/CD automation.

## Project Workflow

1.  Understand the problem
2.  Collect and prepare the dataset
3.  Preprocess and augment images
4.  Train the deep learning model
5.  Track experiments with MLflow
6.  Evaluate model performance
7.  Save and version the model
8.  Build the prediction pipeline
9.  Deploy the application
10. Automate workflows using GitHub Actions

## Features

-   Image preprocessing
-   Data augmentation
-   Transfer Learning
-   Model training
-   Experiment tracking with MLflow
-   Data Version Control (DVC)
-   Model evaluation
-   Prediction pipeline
-   Web application
-   CI/CD automation

## Dataset

The project uses kidney CT scan images for binary image classification.

Classes:

-   Normal
-   Tumor

## Technologies

-   Python
-   TensorFlow / Keras
-   OpenCV
-   NumPy
-   Pandas
-   Matplotlib
-   MLflow
-   DVC
-   Flask or FastAPI
-   GitHub Actions
-   Docker

## Project Structure

``` text
Kidney-Disease-Classification/
├── config/
├── data/
├── artifacts/
├── notebooks/
├── src/
├── pipelines/
├── app/
├── models/
├── mlruns/
├── .github/
│   └── workflows/
├── dvc.yaml
├── params.yaml
├── Dockerfile
├── requirements.txt
└── README.md
```

## Model

The project uses a CNN with Transfer Learning to classify kidney CT scan
images.

## MLOps Components

-   MLflow Experiment Tracking
-   Data Version Control (DVC)
-   Model Versioning
-   GitHub Actions
-   Docker
-   Deployment Pipeline

## Evaluation

-   Accuracy
-   Precision
-   Recall
-   F1 Score
-   Confusion Matrix

## Goal

Learn how to build, track, version, and deploy an end-to-end Deep
Learning application using MLflow, DVC, and modern MLOps practices.
