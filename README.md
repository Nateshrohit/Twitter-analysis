# 📊 Sentiment Analysis of KSI on Twitter

This project was developed as part of the Social Media and Network Analysis (COSC2671) assignment. It involves collecting, preprocessing, and analyzing tweets related to the YouTube and boxing personality **KSI** to understand public sentiment and discover trending discussion topics using Natural Language Processing (NLP) techniques.

---

## 🧠 Project Objective

- Understand public perception of KSI by analyzing a week’s worth of tweets.
- Identify key trending topics (e.g., boxing, product launches).
- Compare sentiment analysis techniques: **TextBlob** and **VADER**.
- Apply **LDA Topic Modeling** to extract discussion themes.

---

## 🔍 Data Collection

- Tweets were collected using the Twitter REST API using Tweepy.
- Fetched 15,000 English-language tweets containing the keyword **"KSI"**.
- Tweets were filtered and stored in a pandas DataFrame.

---

## 🧹 Data Preprocessing

Performed multi-step cleaning and normalization including:
- Lowercasing text (case folding)
- Removing stop words, digits, URLs, mentions, hashtags
- Tokenization & stemming using **Porter Stemmer**

---

## 📈 Exploratory Data Analysis

- Average tweet length: ~109 words
- Frequent keywords: `fight`, `Logan Paul`, `Jake Paul`, `Prime Hydration`
- Top hashtags visualized in bar charts
- Word clouds generated for TextBlob and VADER sentiment results

---

## 🤖 Sentiment Analysis

### 1. **TextBlob**
- Positive: 36.9%
- Neutral: 45.8%
- Negative: 17.3%

### 2. **VADER**
- Positive: 38.6%
- Neutral: 0%
- Negative: 61.34%

---

## 🗣️ Topic Modeling (LDA)

Identified 10 dominant discussion topics including:
- Boxing-related discussions (Jake Paul, Andrew Tate, Bryce Hall)
- Prime Hydration
- Social media slang and trolling

---

## 📌 Insights & Conclusions

- VADER detected more negative tweets due to social-media-tuned lexicon.
- Public sentiment about KSI is mixed, skewed towards negative.
- Popular topics revolve around his boxing career and product promotions.
- Preprocessing significantly improved data quality, reducing noise by over 100,000 words.

---

## 🛠️ Tools & Libraries

- Python
- Pandas, Matplotlib, Seaborn
- Tweepy (Twitter API)
- NLTK, TextBlob, VADER, Gensim (LDA)

---

## 📚 References

- [Getting Started With Textblob](https://www.topcoder.com/thrive/articles/getting-started-with-textblob-for-sentiment-analysis)
- [Tweepy & Twitter API Guide](https://www.youtube.com/watch?v=0EekpQBEP_8)

---

## 🧑‍💻 Author

**Rohit Natesh**  
