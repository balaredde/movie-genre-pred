# 📚 Movie Genre Classification from Plot Descriptions

This project uses **TF-IDF vectorization** and **machine learning algorithms** to classify movies into genres based on their **plot descriptions**.

---

## 🔍 Overview

Given a dataset of movie titles and their plot summaries, this model predicts the most likely **genre** of each movie using classical ML models like:

- Logistic Regression ✅  
- Linear SVM ✅  

> The project supports **single-label classification** and is optimized for high accuracy.

---

## 📁 Dataset

The dataset was sourced from [Kaggle](https://www.kaggle.com/datasets/hijest/genre-classification-dataset-imdb) and contains:
- `ID`, `Title`, `Genre`, and `Description`
- Split into `train`, `test`, and `test_solution` text files

---
# modules
- all ml models and metrics  are avaliable in sklearn 
## 🧠 Features

- **TF-IDF** based feature extraction (`unigrams` and `bigrams`)
- **BERT** bert embedings are also tested 
- **Label encoding** for genre targets
- **Multiple classifiers** trained and compared
- Evaluation using `accuracy`, `precision`, `recall`, and `F1-score`

---

## 🧪 Models Used

| Model               | Status    | Accuracy | Notes                                |
|--------------------|-----------|----------|--------------------------------------|
| Logistic Regression | ✅ Done   | ⭐ High  | Best balance of speed and accuracy   |
| Linear SVM          | ✅ Done   | ⭐⭐ High | Slightly better for sparse features  |


---
