# Sentiment Analysis on BBC News Articles

## 📌 Project Overview
This project applies **Natural Language Processing (NLP)** techniques to evaluate the **sentiment polarity** of BBC News articles. The aim is to assess **market perception** and **public opinion** around business, politics, sports, technology, and entertainment news.

By applying sentiment analysis, the project identifies whether the tone of news coverage is **positive, negative, or neutral**, providing insights that can be used for **market research, trend monitoring, and decision-making**.

---

## 🎯 Objectives
- Load and preprocess BBC News dataset.
- Perform **text cleaning** (lowercasing, punctuation removal, stopword removal, lemmatization).
- Apply **VADER** and **TextBlob** sentiment analysis techniques.
- Compare sentiment distribution across different BBC categories.
- Visualize sentiment trends and key patterns.
- Highlight most positive and most negative articles.

---

## 📂 Dataset Description

### Source
BBC News dataset (same as used in Topic Modelling project) containing:
- **Title** – Headline of the article
- **Description** – Full article content
- **Category** – Predefined BBC section (Business, Entertainment, Politics, Sport, Tech)

### Data Summary
- **Rows:** 2225 articles
- **Columns:** Title, Description, Category
- **Duplicates:** Removed during preprocessing
- **Missing Values:** None

---

## 🛠️ Methodology

### 1️⃣ Data Preprocessing
- Remove duplicates
- Normalize text (lowercase, expand contractions, remove punctuation/numbers)
- Tokenization
- Stopword removal
- Lemmatization

### 2️⃣ Sentiment Analysis Approaches
1. **VADER (Valence Aware Dictionary for Sentiment Reasoning)**
   - Rule-based sentiment scoring optimized for social/media content.
2. **TextBlob**
   - Lexicon-based sentiment scoring with polarity and subjectivity.

### 3️⃣ Sentiment Categorization
- **Positive**: Polarity > 0
- **Neutral**: Polarity = 0
- **Negative**: Polarity < 0

---

## 📊 Results Summary
- **Overall Sentiment**: Majority of articles were **neutral**, followed by **positive**, with fewer **negative** articles.
- **Category Sentiment Trends**:
  - **Sports**: Highest positivity
  - **Politics**: More negative coverage
  - **Business**: Balanced but slightly positive
- **Notable Findings**:
  - Certain news topics consistently carry strong negative sentiment (e.g., scandals, disasters).
  - Positive sentiment often linked to sports wins, tech launches, and cultural events.

---

## 📷 Visualizations
- Sentiment distribution pie chart
- Category-wise sentiment bar chart
- Top positive & negative headlines
- Sentiment word clouds

---

## 📦 Technologies Used
- Python 3.x
- **Libraries:**
  - `pandas`, `numpy`
  - `nltk`
  - `textblob`
  - `matplotlib`, `seaborn`, `wordcloud`
  - `vaderSentiment`

---

## 📈 Business Use Case
Sentiment analysis of news articles can:
- Help **investors** gauge market sentiment for decision-making.
- Enable **brands** to monitor public perception.
- Support **policy analysts** in tracking public opinion on political events.
- Assist **media companies** in understanding audience emotional response.

---

## 🚀 Future Work
- Incorporate **transformer-based sentiment models** (BERT, RoBERTa).
- Perform **time-series sentiment analysis** to track changes over time.
- Link sentiment scores with **real-world market or stock data**.
- Expand to multi-language sentiment analysis.

---


---

## 📜 License
This project is licensed under the PAPM License.

---

## 🙋 Author
**Pragathi Porawakara Arachchige**  
📎 [GitHub Profile](https://github.com/PragathiM007)  
Bellevue University – DSC680 Applied Data Science 
