# 🌸 K-Beauty & Gen Z: What Makes It So Addictive?

*A YouTube-Based Social Listening Study on Consumer Motivations Behind Korean Beauty’s Popularity*

---

## 🎯 Objective

This project explores **why Gen Z is so drawn to K-beauty** — by analyzing YouTube videos, scraping comment sections, and running NLP analysis on over **3,000 real viewer comments**. The goal is to uncover the **emotional tone, product concerns, common skincare motivations**, and **frequently asked questions** around Korean skincare.

---

## 🛠️ Tools & Technologies

- Python
- NLP (TextBlob, NLTK)
- WordCloud & Matplotlib
- YouTube Comment Scraper: [ytdt.digitalmethods.net](https://ytdt.digitalmethods.net)
- Excel
- GitHub

---

## 📁 Project Structure

```bash
K-Beauty-YouTube-Analysis/
├── Data.xlsx                           # Contains influencer list & combined comments
├── kbeauty_word_frequency_summary.csv # Top words used in comments
├── script_1_word_analysis.py          # NLP script for word freq & sentiment
├── script_2_question_analysis.py      # NLP script for detecting and analyzing questions
├── requirements.txt                   # Python dependencies
├── Comments_data/                     # Folder with 16 individual comment CSVs
│   ├── video1.csv
│   ├── video2.csv
│   └── ...
└── README.md                          # You’re reading it!
