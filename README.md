# 🧠 TextBlob Sentiment Analyzer

A simple and interactive sentiment analysis tool built with **TextBlob**.  
This project classifies English sentences as **Positive**, **Negative**, or **Neutral**, and displays color-coded visual feedback.

---

## 📌 Features

- 📖 Classifies text sentiment using TextBlob
- 🎨 Visual feedback with colored backgrounds:
  - 🟢 Positive
  - 🟡 Neutral
  - 🔴 Negative
- 🔍 Displays sentiment polarity score
- 🧪 Works out of the box with sample phrases

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/textblob-sentiment-analyzer.git
cd textblob-sentiment-analyzer
````

### 2. Run the notebook on Google Colab or Jupyter

You can open the project directly in Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/16fxoZcUZD8tqhsAb1w9nin8h_fJOCP4m)

---

## 📦 Requirements

Install dependencies using pip:

```bash
pip install textblob matplotlib numpy
```

Or use this `requirements.txt`:

```txt
textblob==0.17.1
matplotlib==3.8.4
numpy==1.26.4
```

---

## 🧪 Example

```python
from textblob import TextBlob

text = TextBlob("I love programming in Python!")
print(text.sentiment)  # Output: Sentiment(polarity=0.5, subjectivity=0.6)
```

Each sentence is analyzed and displayed with a colored visualization:

> `"I love programming in Python!"`
> 🟢 **POSITIVE** — Polarity: 0.50

---

## 📚 About TextBlob

[TextBlob](https://textblob.readthedocs.io/en/dev/) is a Python library for processing textual data. It provides a simple API for common NLP tasks including:

* Sentiment analysis
* Part-of-speech tagging
* Tokenization
* Noun phrase extraction

---

## 💡 Future Ideas

* 🌍 Add support for Portuguese (`textblob-pt`)
* 📊 Display overall sentiment distribution with plots
* 🗂️ Upload CSV/text files for batch analysis
* 🌐 Create a web interface with Streamlit or Gradio

---

## 📄 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

---
