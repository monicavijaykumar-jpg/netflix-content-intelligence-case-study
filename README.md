# Netflix Content Intelligence: Machine Learning Case Study

A comprehensive machine learning case study and data analysis project developed as part of our college coursework, in collaboration with my two friends. This project explores the Netflix content catalog using advanced data preprocessing, exploratory predictions, supervised classification models implemented in Python.

🔗 **Live Presentation & Case Study Deck:** [View Netlify Presentation](https://mlcasestudy-net-flix.netlify.app)

---

## 🚀 Project Overview
With the massive growth of streaming platforms, understanding content distribution and predicting metadata patterns is essential. This academic case study leverages a comprehensive Netflix dataset to perform end-to-end data analysis and predictive modeling as assigned by our college department.

---

## 🛠️ Tech Stack & Libraries
- **Language:** Python (`.ipynb` / Jupyter Notebook)
- **Data Manipulation & Analysis:** Pandas, NumPy
- **Machine Learning & Preprocessing:** Scikit-Learn
- **Visualization:** Seaborn, Matplotlib
- **Hosting & Deployment:** Netlify (for presentation deck)

---

## 🧹 1. Data Preprocessing
- **Handling Missing Values:** Cleaned and imputed null entries in director, cast, and country attributes, and safely dropped sparse records.
- **Label Encoding & Cleaning:** Converted categorical text classes into numerical integer labels and standardized date formats.
- **TF-IDF Vectorization:** Transformed textual descriptions and summaries into high-dimensional numerical feature vectors for NLP and classification tasks.

---

## 🎯 2. Exploratory Predictions & Insights
As part of our study, we focused on three key predictive insights from the dataset:
1. **Top Content Producing Country:** Identified which countries contribute the highest volume of movies and TV shows to the Netflix platform.
2. **Most Popular & Watched Genres:** Analyzed genre distributions to find which categories dominate the platform and capture maximum viewer engagement.
3. **Top Age Ratings:** Evaluated content distribution across various maturity and age ratings (e.g., TV-MA, PG, TV-14) to understand target audience demographics.

---

## 🤖 3. Supervised Models & Machine Learning
We trained and evaluated robust classifiers to analyze and categorize content:
- **Logistic Regression:** Evaluated as our primary classification model.
- **Random Forest Classifier:** An ensemble tree-based model capturing complex non-linear feature interactions.
- **Support Vector Machine (Linear SVC):** High-margin hyperplane boundary classifier optimized for text feature vectors.

---

## 📈 4. Conclusion & Results
After comparing the performance of all implemented classifiers, **Logistic Regression** achieved the best and most reliable accuracy for our prediction tasks on this dataset. It successfully captured the linear boundaries among features, making it the optimal model for this case study.

---

## ✨ Acknowledgments
This project was successfully designed and implemented as a collaborative college assignment by our team of three. Special thanks to our department faculty for guidance throughout this case study.
