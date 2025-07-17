# ReelFeel_NLP_RNN
![Status](https://img.shields.io/badge/RepoStatus-Public-green)
![Python](https://img.shields.io/badge/Python-3.11-blue)
![License](https://img.shields.io/github/license/MrRincon/FraudCluster_KMeans)

![Owner](https://img.shields.io/badge/Alam-Rincon-orange)
![Owner](https://img.shields.io/badge/Petar-Atanasov-orange)
![Owner](https://img.shields.io/badge/Teon-Morgan-orange)

This project builds a supervised deep learning model to classify IMDB movie reviews as positive or negative. It uses natural language processing (NLP) techniques like HTML cleaning, tokenisation, stopword removal, and lemmatisation. Pre-trained Word2Vec embeddings convert text to numerical form, and a Recurrent Neural Network (RNN) processes the data. Dropout layers and padded sequences help improve performance. The model is evaluated using accuracy, precision, recall, and F1-score, achieving 78.96% accuracy despite computational limits.

---
## Dataset Reference
Lakshmipathi N. (2019) ‘IMDB Dataset of 50K Movie Reviews’. Available at: https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews (Accessed: 14 April 2025).

---
## Problem Solved 
The project solves the problem of classifying IMDB movie reviews as either positive or negative. It replaces the need for manual sentiment analysis by using supervised learning and natural language processing to automatically predict the sentiment of each review.

---
## Motivation
The motivation behind this project is to address the challenge of analysing large volumes of movie reviews, where manual sentiment analysis is inefficient and inconsistent. Automating this process using NLP and supervised learning enables faster and more reliable understanding of public opinion.

---
## Requirements
  ### Jupyter Setup
    - Install Anaconda (Python 3.11+ recommended).
    - Launch JupyterLab via Anaconda Navigator.
    - Use a Python 3 kernel in JupyterLab.
  ### Colab Setup
    - Add the project in a folder, include also the dataset into it.
    - Mount the drive on the notebook at the beginning.
  ### Project Setup Instructions
    - Clone the repository and create a folder called 'datasets' in the root directory.
    - Download the dataset from Kaggle and place the .csv file in the dataset folder.

## Table of Contents
1. Project Overview
2. Datset Reference
3. Problem Solved
4. Motivation
5. Requirements
  - Jupyter Setup
  - Colab Setup
  - Project Setup Instructions
6. Notebook Structure
  - Preinstalling Libraries
  - Preprocessing Data
  - Deep Learning Model Implementation
    - Recurrent Neural Network (RNN) Model
    - Model Training
  - Evaluation and Insights
