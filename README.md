# Caravan Insurance Purchase Prediction

## Overview

This project aims to predict customer interest in purchasing caravan insurance. The goal is to build a **binary classification model** using supervised machine learning techniques.

---

## Problem Statement

### Context

An insurance company needs to identify potential customers who are interested in purchasing caravan insurance. By analyzing customer characteristics, the company can target its campaigns more effectively.

### Objective

Develop a machine learning model that predicts whether a customer is interested in buying caravan insurance based on **85 input features**.

---

## Data Description

- **Training Data**: 5,822 samples with 85 features and a target variable (`Caravan_Insurance`).
- **Test Data**: 4,000 samples with 85 features (no target variable).
- **Target Variable**:  
  - `Caravan_Insurance` (1 = Interested, 0 = Not Interested)  

The dataset exhibits **class imbalance**, where the number of "Interested" customers is significantly lower.

---

## Project Workflow

1. **Data Exploration and Preprocessing**  
   - Check for missing values.  
   - Visualize the target variable distribution.  
   - Handle class imbalance.

2. **Feature Engineering**  
   - Normalize/standardize features.  
   - Select significant features if necessary.

3. **Model Development**  
   - Train multiple classification models (e.g., Logistic Regression, Random Forest, etc.).  
   - Evaluate model performance using appropriate metrics.

4. **Model Evaluation**  
   - Metrics used include:  
     - Accuracy  
     - Precision, Recall, and F1-score  
     - ROC-AUC  

---

## Installation and Requirements

### Prerequisites

Ensure you have Python installed. The following libraries are used:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

### Installation

Install required dependencies using:

```bash
pip install -r requirements.txt
