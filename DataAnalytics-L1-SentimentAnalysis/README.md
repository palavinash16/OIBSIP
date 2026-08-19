# 💬 Sentiment Analysis Using NLP & Machine Learning

**Oasis Infobyte Internship (OIBSIP)**  
**Track**: Data Analytics  
**Level / Task**: Level 1 - Task 4 (`OIBSIP/DataAnalytics-L1-SentimentAnalysis`)  
**Author**: Data Analytics Intern  

---

## 📌 Project Overview
Sentiment Analysis is a critical **Natural Language Processing (NLP)** application that enables organizations to extract public opinion, customer emotion, and feedback polarity from unstructured text data. This project develops an end-to-end NLP classification pipeline that cleans customer feedback reviews, extracts **TF-IDF numerical features**, trains **Multinomial Naive Bayes** and **Logistic Regression** models, visualizes sentiment WordClouds, and conducts an in-depth error analysis.

---

## 📊 Feature Checklist Compliance

| Checklist Item | Requirement Status | Implementation Details |
| :--- | :---: | :--- |
| **Data Quality & Class Distribution** | ✅ Complete | Inspected 1,800 reviews across Positive (45%), Negative (35%), and Neutral (20%) classes |
| **Text Preprocessing Pipeline** | ✅ Complete | Applied lowercasing, punctuation/digit removal, tokenization, and NLTK stopword filtering |
| **TF-IDF Feature Extraction** | ✅ Complete | Transformed text using `TfidfVectorizer(max_features=1500, ngram_range=(1,2))` with markdown formulas |
| **Train/Test Split** | ✅ Complete | Performed stratified 80/20 train/test split preserving class ratios |
| **Multi-Classifier Model Training** | ✅ Complete | Trained and compared **Multinomial Naive Bayes** and **Logistic Regression** classifiers |
| **Model Evaluation Metrics** | ✅ Complete | Computed Accuracy, Precision, Recall, F1-Score, and plotted Confusion Matrix heatmaps |
| **WordCloud Visualizations** | ✅ Complete | Generated custom-themed WordClouds for Positive, Negative, and Neutral text |
| **Error & Edge Case Analysis** | ✅ Complete | Evaluated 5 challenging edge cases (sarcasm, double negatives, mixed sentiment) |
| **Conclusion & Real-World Use Cases** | ✅ Complete | Outlined 3 real-world business applications (support routing, reputation tracking, defect detection) |

---

## 🛠️ Tech Stack & Libraries
- **Language**: Python 3.x
- **NLP & Text Processing**: `nltk` (Stopwords, Tokenizer, RegEx), `WordCloud`
- **Machine Learning**: `scikit-learn` (`TfidfVectorizer`, `MultinomialNB`, `LogisticRegression`)
- **Data Analysis & Visualization**: `pandas`, `numpy`, `matplotlib`, `seaborn`
- **Environment**: Jupyter Notebook / Anaconda

---

## 🤖 Model Performance Summary

| Classifier Model | Test Accuracy | Precision (Macro) | Recall (Macro) | F1-Score (Macro) | Confusion Matrix Highlights |
| :--- | :---: | :---: | :---: | :---: | :--- |
| **Multinomial Naive Bayes** | **100.0%** | **1.00** | **1.00** | **1.00** | Perfect class separation across test split |
| **Logistic Regression** | **100.0%** | **1.00** | **1.00** | **1.00** | Optimal linear hyper-plane separation |

---

## 🚀 Real-World Business Applications

1. 🎧 **Automated Support Ticket Routing**: Automatically route negative sentiment reviews to high-priority customer support queues for immediate resolution.
2. 📈 **Brand Reputation & Social Listening**: Track real-time public sentiment across social media platforms, app stores, and e-commerce product listings.
3. 💡 **Product Defect Identification**: Extract recurring negative sentiment clusters to pinpoint hardware or software issues for engineering product teams.

---

## 📂 Project Repository Structure

```text
OIBSIP/DataAnalytics-L1-SentimentAnalysis/
├── Sentiment_Analysis_Data.csv    # Product review text dataset with sentiment labels
├── main.ipynb                     # Fully executed Jupyter Notebook with NLP pipeline, models & WordClouds
└── README.md                      # Detailed project documentation & task checklist compliance
```

---

## 📽️ Demo Video Instructions for Submission
When recording the screen walkthrough for LinkedIn & task submission:
1. **Title Card (First 2 Seconds)**: Display a static frame with:
   - Full Name
   - Track: Data Analytics
   - Task Title: Level 1 Task 4 - Sentiment Analysis
2. **Walkthrough**: Narrate through the executed notebook, highlighting the text preprocessing pipeline, TF-IDF feature extraction explanation, WordCloud visualizations, Confusion Matrices, and Error Analysis.
3. **LinkedIn Post**: Tag **Oasis Infobyte** with `#oasisinfobyte #dataanalytics #sentimentanalysis #nlp #scikitlearn #python`.
