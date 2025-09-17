# Book-Recommendor-
A machine learning project that builds a content-based book recommendation system using data sourced from Kaggle Hub . The system leverages natural language processing (NLP) techniques and similarity metrics to recommend books based on a given input title.

  # 📚 Book Recommendation System  

[![Python](https://img.shields.io/badge/Python-3.8+-blue?logo=python&logoColor=white)](https://www.python.org/)  
[![scikit-learn](https://img.shields.io/badge/scikit--learn-1.5-orange?logo=scikitlearn&logoColor=white)](https://scikit-learn.org/)  
[![Pandas](https://img.shields.io/badge/Pandas-1.5+-150458?logo=pandas&logoColor=white)](https://pandas.pydata.org/)  
[![Kaggle Dataset](https://img.shields.io/badge/Dataset-Kaggle-blue?logo=kaggle&logoColor=white)](https://www.kaggle.com/)  
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)  

A **content-based book recommendation system** built using data from Kaggle.  
The system uses **vectorization (CountVectorizer)** and **cosine similarity** to recommend books similar to a user’s input.  

---

## 🚀 Overview  

This project demonstrates how **content-based filtering** can be used to build a simple recommendation system.  
By analyzing book metadata (titles, authors, publishers), the system suggests books that are semantically close to a given title.  

---

## ⚙️ Tech Stack  

- **Python 3.8+**  
- **Pandas** → Data cleaning & manipulation  
- **scikit-learn (sklearn)** → CountVectorizer, Cosine Similarity  
- **Numpy** → Numerical operations  
- **Jupyter Notebook / VS Code**  

---

## 📂 Dataset  

- **Source**: [Kaggle Hub – Books Dataset](https://www.kaggle.com/)  
- **Features Used**:  
  - `Book-Title`  
  - `Book-Author`  
  - `Publisher`  

- **Dropped Columns**:  
  - `ISBN`  
  - `Year-Of-Publication`  
  - Image URLs  

---

## 🧠 Methodology  

1. **Data Cleaning** → removed unnecessary columns, normalized text.  
2. **Vectorization** → used **CountVectorizer** to convert titles into vectors.  
3. **Similarity Calculation** → applied **cosine similarity** to measure closeness.  
4. **Recommendation Engine** → retrieves **Top N similar books** for any input title.  

---

## 📊 Example  

**Input**:  
```python
"Far Beyond the Stars (Star Trek Deep Space Nine)"

