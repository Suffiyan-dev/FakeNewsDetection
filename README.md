# 📰 Fake News Detection Project

## 📌 Project Overview
This project focuses on building a **Fake News Detection System** using **Machine Learning** and **NLP** techniques.  
The goal is to classify news articles as **FAKE** or **REAL**. The project includes **data preprocessing**, **exploratory data analysis**, **model training**, and deployment through an **interactive Streamlit app**.

---

---

## 🛠️ Tech Stack
- **Python 3.9+**  
- **Libraries:**  
  - Pandas, NumPy (Data handling)  
  - Scikit-learn (ML models)  
  - Matplotlib, Seaborn (Visualization)  
  - NLTK (Text preprocessing)  
  - Streamlit (Deployment)

---

## 📊 Dataset
- **Files:** `fake.csv` (fake news), `true.csv` (real news)  
- **Columns:**  
  - `title` → News title  
  - `text` → Full article text  
  - `subject` → News category  
  - `date` → Publish date  
- **Labeling:** FAKE = 1, REAL = 0 (created during preprocessing)

---

## 🔍 Steps Performed

### 1. Data Preprocessing
- Combined fake and true datasets into one DataFrame.  
- Cleaned text: removed punctuation, stopwords, lowercase, lemmatization.  
- Created a `label` column: FAKE = 1, REAL = 0.  

### 2. Exploratory Data Analysis (EDA)
- Analyzed article length and word counts.  
- Most common words in fake and real news (WordClouds).  
- Visualized distribution of FAKE vs REAL news.  

### 3. Model Training
- Converted text to numerical features using **TF-IDF Vectorizer**.  
- Tested models: **Logistic Regression**, **Naive Bayes**, **Random Forest**.  
- Evaluated models using **Accuracy, Precision, Recall, F1-score**.  
- Best model chosen: **Logistic Regression**.  

### 4. Streamlit App
- Interactive web app to predict whether a news article is FAKE or REAL.  
- Features:
  - Input text manually or upload CSV.  
  - Show prediction with probability/confidence.  
  - Display basic visualizations from dataset (optional).  

---


