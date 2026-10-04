# Netflix Content Intelligence: Machine Learning Case Study

A comprehensive machine learning case study and data analysis project developed as part of our college coursework, in collaboration with my two friends. This project explores the Netflix content catalog using advanced data preprocessing, supervised classification models implemented in Python.

🔗 **Live Presentation & Case Study Deck:** [View Netlify Presentation](https://mlcasestudy-net-flix.netlify.app)

---

## 🚀 Project Overview
With the massive growth of streaming platforms, understanding content distribution and predicting metadata patterns is essential. This academic case study leverages a Kaggle dataset containing 8,800+ rows and 12 distinct attributes of movies and TV shows to perform end-to-end exploratory data analysis and predictive modeling.

---

## 🛠️ Tech Stack & Libraries
- **Language:** Python (`.ipynb` / Jupyter Notebook)
- **Data Manipulation & Analysis:** Pandas, NumPy
- **Machine Learning & Preprocessing:** Scikit-Learn
- **Visualization:** Seaborn, Matplotlib
- **Hosting & Deployment:** Netlify (for presentation deck)

---

## 📊 Methodology & Pipeline

### 1. Data Preprocessing
- **Handling Missing Values:** Cleaned and imputed null entries in director and cast attributes, and safely dropped sparse records.
- **Label Encoding:** Converted categorical text classes into numerical integer labels.
- **TF-IDF Vectorization:** Transformed textual descriptions and summaries into high-dimensional numerical feature vectors for NLP and classification tasks.

### 2. Supervised Classification Models
We trained and evaluated three robust classifiers to predict target categories:
- **Logistic Regression:** Used as a baseline linear classifier.
- **Random Forest Classifier:** An ensemble tree-based model capturing complex non-linear feature interactions.
- **Support Vector Machine (Linear SVC):** High-margin hyperplane boundary classifier optimized for text feature vectors.

---

## 📂 Repository Structure
```text
├── notebook/
│   └── netflix_machine_learning_case_study.ipynb   # Complete Python pipeline & code
├── README.md                                      # Project documentation
