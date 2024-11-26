
# Fault Prediction  

This repository contains the implementation of a **Fault Prediction in Transmission Lines** project. The objective of the project is to predict faults in Nigeria's transmission lines using machine learning models. The project was developed and executed on **Google Colab**, making use of its computational resources and seamless integration with Google Drive for data handling.

---

## Table of Contents

1. [Overview](#overview)
2. [Features](#features)
3. [Dataset](#dataset)
4. [Models Evaluated](#models-evaluated)
5. [Results](#results)

---

## Overview

Transmission line faults can result in power outages, economic losses, and infrastructure damage. This project aims to use machine learning models to predict potential faults, thereby enabling proactive measures to reduce downtime and enhance the reliability of power systems.

The repository includes:
- Data preprocessing steps
- Training and evaluation of machine learning models
- Visualization of results and model comparison

---

## Features

- Fault classification using machine learning
- Implementation of multiple algorithms for performance comparison
- Model evaluation using key metrics such as accuracy
- Designed to be easily executed on **Google Colab**

---

## Dataset

The dataset for this project includes:
- Historical records of transmission line faults.
- Features representing environmental, operational, and equipment-related factors.

The dataset is stored in **Google Drive** and is mounted directly to the Colab environment during execution.

---

## Models Evaluated

The following machine learning models were evaluated in this project:
- **Quadratic Discriminant Analysis (QDA):** Achieved the highest accuracy.
- **K-Nearest Neighbors (KNN):** Performed well, second to QDA.
- **Linear Discriminant Analysis (LDA):** Exhibited the lowest accuracy.



## Results

| Model                | Accuracy  |  
|----------------------|-----------|  
| **QDA**              | Highest   |  
| **KNN**              | High      |  
| **LDA**              | Lowest    |  

Key takeaways:
- QDA is the most suitable model for this dataset.
- KNN offers a close alternative, especially when computational efficiency is important.
- LDA underperforms compared to the other two.

---



