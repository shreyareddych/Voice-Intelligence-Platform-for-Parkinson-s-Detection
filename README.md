# Voice Intelligence Platform for Parkinson's Disease Detection

## Overview

This project presents a comparative analysis of machine learning models for Parkinson's disease detection using speech-derived biomedical features from the Parkinson's UPDRS dataset. Multiple classification algorithms are trained and evaluated under a unified experimental pipeline to identify the most effective model for disease prediction.

## Features

* Data preprocessing and feature preparation for Parkinson's disease prediction
* Comparative evaluation of multiple machine learning classifiers
* Standardized training and testing workflow across all models
* Performance assessment using Accuracy, Precision, Recall, and F1-Score
* Confusion matrix-based model evaluation

## Project Structure

```plaintext
Voice-Intelligence-Platform-for-Parkinsons-Detection/
│
├── gradient_boosting.py
├── lr.py
├── rf.py
├── knn.py
├── parkinsons_updrs.data
├── parkinsons_updrs.names
└── README.md
```

## Dataset

The project uses the Parkinson's UPDRS dataset containing speech-related biomedical measurements associated with Parkinson's disease progression.

## Models Implemented

* Logistic Regression
* Gradient Boosting
* Random Forest
* K-Nearest Neighbors (KNN)

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib

## Installation

```bash
git clone https://github.com/shreyareddych/Voice-Intelligence-Platform-for-Parkinson-s-Detection.git
cd Voice-Intelligence-Platform-for-Parkinson-s-Detection
pip install pandas numpy scikit-learn matplotlib
```

## Run the Models

```bash
python lr.py
python gradient_boosting.py
python rf.py
python knn.py
```

## Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

## Future Enhancements

* Automated audio feature extraction using Librosa
* Deep learning-based speech classification
* Real-time prediction interface
* Model deployment as a web application




