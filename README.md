# Multi-Aspect Sentiment Analysis of Indonesian Hotel Reviews

This repository contains the complete code, data, and models for the undergraduate thesis titled:  
**"Multi-Aspect Sentiment Analysis of Indonesian Hotel Reviews Using Hybrid Classifier Based on SVM, NB, RF, and K-NN with TF-IDF Representation."**

The research evaluates and compares the performance of four individual machine learning models against a proposed hybrid stacking classifier on the **HoASA** (Hotel Aspect-Based Sentiment Analysis) dataset from the **IndoNLU** benchmark.

---

## 📂 Repository Structure

The project is organized into the following directories:

- `/data`: Contains all datasets used in the research.
  - `/data/raw`: Includes the original and cleaned review data (`train_cleaned.csv`, `test_cleaned.csv`).
  - `/data/processed`: Contains the feature-engineered datasets resulting from the vectorization process (`bow_train.csv`, `tfidf_train.csv`, `w2v_train.csv`, etc.).
- `/models`: Contains the saved (pickled) vectorizer and Word2Vec models for reproducibility.
- `/notebooks`: Contains all the Jupyter Notebooks (`.ipynb`) used for the implementation of this research. The notebooks cover:
  - Data preprocessing and cleaning
  - Feature extraction (BoW, TF-IDF, Word2Vec)
  - Training and evaluation of individual baseline models
  - Implementation of data balancing techniques
  - Training and evaluation of the final hybrid stacking classifier

---

## 🚀 How to Run

To reproduce the results of this research, please follow these steps:

### 1. Clone the Repository

``bash
git clone https://github.com/AzhaMewar/Multi-Aspect-Sentiment-Analysis.git
cd Multi-Aspect-Sentiment-Analysis

### 2. Install Dependencies
pip install pandas scikit-learn gensim notebook imbalanced-learn

### 3. Run the Notebooks
Open the Jupyter Notebooks located in the /notebooks directory and run the cells in sequential order to replicate the experiments.
The data and models will be loaded from their respective directories.

#### 🛠️ Technologies & Libraries Used
- Language: Python 3.9
- Environment: Jupyter Notebook
- Core Libraries: you can see on the each notebooks
