# 🧠 Sentiment Analysis using BERT

This project performs sentiment analysis on customer reviews using the pre-trained BERT model from Hugging Face (`nlptown/bert-base-multilingual-uncased-sentiment`).

---

## 📌 Overview

The model classifies reviews into sentiment categories (1 to 5 stars). Reviews are scraped from a website (Yelp) and passed through a fine-tuned multilingual BERT model to generate sentiment scores.

---

## 🚀 Features

- ✅ Web scraping using BeautifulSoup
- ✅ Tokenization using HuggingFace Transformers
- ✅ Sentiment scoring using BERT
- ✅ DataFrame construction for visualization/analysis

---

## 🛠️ Installation

Install all required packages using:

```bash
pip install -r requirements.txt
