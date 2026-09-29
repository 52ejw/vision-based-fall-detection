# Real-Time Vision-Based Human Fall Detection

This repository contains the Jupyter notebooks developed for my Final Year Project (FYP), **“Real-Time Vision-Based Human Fall Detection Using Pose Estimation and Deep Temporal Learning.”**

The project explores the use of human pose estimation and deep learning models to detect falls from video data in real time, with the aim of supporting non-wearable fall monitoring.

## Project Overview

The system processes video frames to extract human body pose information and uses temporal deep learning models to classify activities as either **fall** or **non-fall**.

The project focuses on:

* Human pose estimation using **MediaPipe**
* Video and image processing using **OpenCV**
* Pose feature extraction using **NumPy**
* Deep learning-based temporal classification using **TensorFlow/Keras**
* Model evaluation and comparison using **scikit-learn**

## Repository Structure

```text
├── notebooks/
│   ├── data_preprocessing.ipynb
│   ├── model_training.ipynb
│   └── model_evaluation.ipynb
│
└── .gitignore
```

### Notebooks

**`data_preprocessing.ipynb`**
Handles dataset preparation, preprocessing, pose extraction, feature generation, and preparation of data for model training.

**`model_training.ipynb`**
Contains the development and training of the deep learning models used for fall detection.

**`model_evaluation.ipynb`**
Evaluates and compares the trained models using relevant classification metrics.

## Models

The project investigates several deep learning architectures for temporal fall detection, including:

* Simple LSTM
* Stacked LSTM
* Bidirectional LSTM (BiLSTM)
* GRU
* CNN-LSTM

## Technologies

* Python
* Jupyter Notebook
* OpenCV
* MediaPipe
* NumPy
* TensorFlow / Keras
* scikit-learn

## Dataset

The project uses publicly available human activity and fall-detection datasets.

Due to their size and licensing considerations, the datasets are **not included in this repository**. The required datasets should be obtained from their respective official sources and placed in the appropriate local data directories.

## Computing Environment

Model training and computationally intensive experiments are performed on a **GPU-enabled High Performance Computing (HPC) environment** provided by the university.

The notebooks are therefore intended to be run in a suitable Python environment with the required dependencies and access to the datasets.

## Project Status

This repository is currently under development as part of my Final Year Project.

More documentation, experimental results, and implementation details will be added as the project progresses.
