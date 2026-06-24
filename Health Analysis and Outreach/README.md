# Machine Learning Healthcare Prediction Project

## Overview

This repository contains machine learning models and datasets related to healthcare analytics and patient admission prediction.

The project includes:

* **ASA Rating Prediction Model** – Predicts a patient's ASA (American Society of Anesthesiologists) physical status classification.
* **Length of Stay Prediction Model** – Predicts the expected number of days a patient will stay in the hospital.

---

## Files

### Models

#### `asa.pkl`

Machine learning model used to predict the **ASA Rating** of a patient based on the provided clinical features.

#### `day.pkl`

Machine learning model used to predict the **Length of Stay (LOS)** in days for a patient.

---

### Datasets

#### `MRN.csv`

The complete dataset used during data preprocessing, analysis, and model development.

#### `HDHI Admission data.csv`

A smaller and storage-efficient version of the admission dataset used for experimentation, training, and testing.

---

### Notebooks

#### `ASA.ipynb`

Jupyter notebook containing:

* Data preprocessing
* Feature engineering
* Model training
* ASA Rating prediction workflow

#### `Day_HDHI.ipynb`

Jupyter notebook for predicting hospital stay duration using the HDHI Admission dataset.

#### `Day_MRN.ipynb`

Jupyter notebook for predicting hospital stay duration using the MRN dataset.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Joblib
* Jupyter Notebook

---

## Project Objectives

1. Predict patient ASA Rating.
2. Estimate hospital length of stay.
3. Explore healthcare admission datasets.
4. Build and evaluate machine learning models for clinical decision support.

---

## Dataset Information

The datasets included in this project are intended for educational and research purposes.

* **MRN.csv** contains the full dataset used for model development.
* **HDHI Admission data.csv** is a reduced-size version for easier storage and experimentation.

---

## Author

**Ahmed Almas**

GitHub: https://github.com/Ahmed-Almas
