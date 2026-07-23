# Chicken Disease Classification

## Overview

This project is an end-to-end Deep Learning application that classifies
chicken diseases from poultry images using Convolutional Neural Networks
(CNNs) and Transfer Learning.

The project covers the complete MLOps workflow, including data
versioning with DVC, model training, deployment, and CI/CD automation.

## Project Workflow

1.  Understand the problem
2.  Collect and prepare the dataset
3.  Preprocess and augment images
4.  Train the deep learning model
5.  Evaluate model performance
6.  Save the trained model
7.  Build the prediction pipeline
8.  Deploy the application
9.  Track datasets and models using DVC
10. Automate workflows using GitHub Actions

## Features

-   Image preprocessing
-   Data augmentation
-   Transfer Learning
-   Model training
-   Model evaluation
-   Prediction pipeline
-   Web application
-   DVC integration
-   GitHub Actions
-   Docker support

## Dataset

-   Healthy
-   Coccidiosis
-   Newcastle Disease
-   Salmonella

## Technologies

-   Python
-   TensorFlow / Keras
-   OpenCV
-   NumPy
-   Pandas
-   Matplotlib
-   DVC
-   Flask or FastAPI
-   GitHub Actions
-   Docker

## Project Structure

``` text
Chicken-Disease-Classification/
├── config/
├── data/
├── artifacts/
├── notebooks/
├── src/
├── pipelines/
├── app/
├── models/
├── .github/
│   └── workflows/
├── dvc.yaml
├── params.yaml
├── Dockerfile
├── requirements.txt
└── README.md
```

## Model

The project uses a CNN with Transfer Learning to classify poultry
diseases from images.

## MLOps Components

-   DVC
-   Model Versioning
-   GitHub Actions
-   Docker
-   Deployment Pipeline

## Goal

Learn how to build, train, version, deploy, and maintain a Deep Learning
application using modern MLOps practices.
