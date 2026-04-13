# 📘 Week 07 — NLP Assignment

**TF-IDF, Embeddings, Sentiment & Model Evaluation**

---

## 📌 Overview

This assignment focuses on building a strong foundation in Natural Language Processing (NLP) by implementing **TF-IDF from scratch**, performing **document ranking using cosine similarity**, and understanding **term importance using IDF**.

The goal is to understand how text is transformed into numerical representations and how relevance between documents is computed.

---

## 📁 Folder Structure

```
week07/
└── monday/
    ├── Assignment.ipynb
    ├── README.md
```

---

## 📂 Dataset

The assignment uses the **ShopSense E-Commerce Reviews Dataset (10K reviews)**.

**Columns include:**

* `review_text` — Customer review content
* `category` — Product category (Electronics, Clothing, etc.)
* `rating` — Rating (1–5)
* `sentiment_label` — Sentiment (Positive/Negative)

---

## 🚀 Tasks Performed

### 🔹 Q1 — TF-IDF from Scratch

* Implemented TF-IDF without using sklearn
* Built vocabulary manually
* Computed:

  * Term Frequency (TF)
  * Inverse Document Frequency (IDF)
  * TF-IDF matrix
* Ranked top-5 relevant reviews using **cosine similarity**
* Compared results with sklearn’s `TfidfVectorizer`
* Identified top TF-IDF word in **Electronics category**

---

### 🔹 Q2 — Manual Computation & Theory

* Calculated TF, IDF, TF-IDF manually for a selected word
* Verified results using code
* Compared IDF of common vs rare words
* Explained importance of TF-IDF over simple frequency

---

## 🛠️ Technologies Used

* Python 🐍
* NumPy
* Pandas
* Regular Expressions (for preprocessing)

---

## ⚙️ Preprocessing Steps

* Removed HTML tags
* Converted text to lowercase
* Removed special characters
* Tokenized text into words
* Removed stopwords

---

## ▶️ How to Run

1. Clone the repository:

```bash
git clone https://github.com/aditi23garg/week07
```

2. Navigate to folder:

```bash
cd week07/monday
```

3. Install dependencies:

```bash
pip install numpy pandas scikit-learn
```

4. Run the notebook:

```bash
jupyter notebook
```

---

## 📊 Output

* TF-IDF matrix generated from scratch
* Top-5 ranked reviews for a query
* Comparison with sklearn TF-IDF (L2 difference)
* Identification of most important words per category
* Manual and programmatic TF-IDF calculations

---

## 💡 Key Learnings

* How TF-IDF balances frequency and importance
* Why common words have low importance (low IDF)
* How cosine similarity helps in document ranking
* Difference between TF-IDF and BM25
* Importance of preprocessing in NLP

---

## ✅ Notes

* All implementations are done **from scratch (no sklearn for TF-IDF)**
* Proper modular functions are used for clarity
* Edge cases like missing values and zero division are handled

