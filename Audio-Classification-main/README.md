# Audio Classification using UrbanSound8K

## Overview

This project builds a Deep Learning model to classify environmental
sounds using the UrbanSound8K dataset.

The project covers the complete Machine Learning workflow, including
audio preprocessing, feature extraction, model training, evaluation, and
deployment.

## Project Workflow

1.  Understand the problem
2.  Download the UrbanSound8K dataset
3.  Explore the dataset
4.  Preprocess audio files
5.  Extract MFCC features
6.  Train a Deep Learning model
7.  Evaluate model performance
8.  Save the trained model
9.  Build the prediction pipeline
10. Deploy the application

## Dataset

This project uses the **UrbanSound8K** dataset, which contains 8,732
labeled audio clips across 10 environmental sound classes.

### Download Dataset

https://urbansounddataset.weebly.com/download-urbansound8k.html

## Sound Classes

-   Air Conditioner
-   Car Horn
-   Children Playing
-   Dog Bark
-   Drilling
-   Engine Idling
-   Gun Shot
-   Jackhammer
-   Siren
-   Street Music

## Features

-   Audio preprocessing
-   MFCC feature extraction
-   Deep Learning classification
-   Model evaluation
-   Prediction pipeline
-   Audio inference
-   Web application
-   Model deployment

## Technologies

-   Python
-   TensorFlow / Keras
-   Librosa
-   NumPy
-   Pandas
-   Matplotlib
-   Scikit-learn
-   Flask or FastAPI
-   Docker (Optional)

## Project Structure

``` text
Audio-Classification/
├── data/
├── notebooks/
├── src/
├── models/
├── app/
├── artifacts/
├── requirements.txt
├── README.md
└── Dockerfile
```

## Model

The project uses a CNN trained on MFCC audio features to classify
environmental sounds.

## Evaluation

-   Accuracy
-   Precision
-   Recall
-   F1 Score
-   Confusion Matrix

## Goal

Learn how to build an end-to-end Deep Learning application for audio
classification from raw audio preprocessing to deployment.
