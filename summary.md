# AI Generated Document Summary

---

## Document Information

| Property | Value |
|----------|-------|
| File Name | 8fa67f27-2603-41d9-90e8-07b8e854ed4f-PPT-Session-1 (2).pdf |
| Pages | 100 |
| Characters | 38257 |
| Generated On | 2026-07-03 12:11:17 |

---

## Table of Contents

- Overview
- Key Concepts
- Important Details
- Summary

---

# Introduction to Artificial Intelligence: Machine Learning and Deep Learning

## Overview

This document covers the foundational concepts of artificial intelligence (AI), machine learning, and deep learning, including historical milestones, key concepts, and important details. It also delves into modern AI techniques, supervised learning, and the challenges faced during the development of AI technologies.

## Key Concepts

### Artificial Intelligence (AI)
- **Definition**: Automation of human-like thinking, decision-making, and problem-solving.
- **Four Quadrant Framework**: Think/Act × Human/Rational.
- **Modern AI Focus**: Acting rationally rather than necessarily like humans.

### Machine Learning
- **Definition**: Techniques for training models to improve performance on tasks.
- **Data**: Essential for machine learning, categorized as categorical, ordinal, or continuous.
- **Tom Mitchell's Definition**: A computer program learns from experience if its performance on a task improves with more experience.
- **Supervised Learning**: Training models using labeled data to map inputs to outputs.

### Data
- **Volume**: 333 billion emails sent daily, 8.5 billion Google searches, and a global datasphere expected to reach 90ZB by 2025.
- **Labeling**: Only about 1% of data is labeled, crucial for supervised learning.

## Important Details

### Introduction to Artificial Intelligence: Machine Learning and Deep Learning

- **Historical Milestones**:
  - **Turing Test**: Introduced in 1950.
  - **First AI Winter**: 1970s due to high costs and failure to meet expectations.
- **Good Old AI Days**:
  - **Representing Knowledge**:
    - **Logic**: Formal symbolic reasoning using propositions, predicates, and inference rules.
    - **Rules**: If-then production rules encoding expert knowledge.
    - **Semantic Graphs/Nets**: Graph-based representation of concepts and relationships.
  - **Challenges Leading to AI Winter**:
    - **Ambiguity**: High-funding translation programs failed at semantic disambiguation.
    - **Scalability & Complexity**: Early AI examples were small and narrowly scoped.
    - **Representation Limitations**: Knowledge representation schemes were brittle and couldn't handle uncertainty, ambiguity, or common sense.
- **Key Periods**:
  - **Boom 1**: GOFAI (General-purpose AI) in the 1960s.
  - **Winter 1**: 1970s.
  - **Boom 2**: Expert systems in the 1980s.
  - **Winter 2**: 1990s.
  - **Boom 3**: Machine learning in the 2000s.

### Machine Learning

- **Data Volume**: 333 billion emails sent daily, 8.5 billion Google searches, and a global datasphere expected to reach 90ZB by 2025.
- **Data Labeling**: Only about 1% of data is labeled, crucial for supervised learning.
- **Three Booms and Two Winters**: Cyclical periods of increased funding and progress followed by reduced funding and stagnation.
- **AI Winter Periods**: 1970s (Winter 1) and 1990s (Winter 2).
- **Supervised Learning Workflow**: Involves feature extraction and training/evaluation phases.
- **Quiz**: The primary purpose of splitting data into training and test sets is to prevent overfitting and evaluate generalization.

### Supervised Learning using scikit-learn

- **Problem**: Breast cancer prediction as a binary classification problem.
- **Target Labels**: Malignant (cancerous), Benign (non-cancerous).
- **Train-Test Split**: `train_test_split(X, y, test_size=0.2, random_state=42)`.
- **Feature Scaling**: 
  - **Logistic Regression**: Scale-sensitive.
  - **Standardization**: Mean and standard deviation.
  - **Min-Max Scaling**: Range normalization.
- **Model Training**: `from sklearn.linear_model import LogisticRegression`, `model = LogisticRegression(max_iter=1000)`, `model.fit(X_train, y_train)`.

### Data Generation and Volume

- **Data Volume**: The world generates data in Zettabytes, with 1 Zettabyte equating to 1 trillion Gigabytes.
- **Labeling**: Most data is unlabelled, requiring human effort, time, and domain expertise.
- **Unsupervised Learning**: Techniques for discovering hidden structures without labeled data.

### Anomaly Detection and Unsupervised Learning

- **Anomaly Detection**: Flagging transactions or patterns that deviate significantly from the norm.
- **High-Dimensional Data**: Data with many dimensions, such as images, text, and genomics.
- **Curse of Dimensionality**: Challenges in high-dimensional spaces where distances lose meaning.
- **Feature Extraction Bottleneck**: Limitation in traditional machine learning requiring human expertise.

### Neural Networks and Activation Functions

- **Weighted Sum**: The sum of input values multiplied by their respective weights plus a bias term.
- **Activation Function**: Transforms the weighted sum to produce the final output.
- **Non-Linearity**: Introduces complexity beyond simple linear separability.
- **ReLU Neurons**: Draw one line per neuron, keeping lines independent.
- **Universal Approximation Theorem**: Non-linear layers enable complex boundaries.
- **Backpropagation**: Algorithm for training neural networks by calculating the gradient of the loss function with respect to the network's weights.

### Modern Optimizers and Backpropagation

- **Vanishing Gradients**: A challenge in deep neural networks where gradients become very small during backpropagation, hindering learning.
- **Overfitting**: Occurs when a model

---

## Generated By

This document was automatically generated using the **AI GitHub Agent**.

