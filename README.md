


# 🧠 NLP Stack Overflow Mini-Project

This project was developed as part of the **Applied Natural Language Processing (4533_COMP_SCI_7417_7717)** course at the **University of Adelaide**. It involves collecting, preprocessing, analyzing, and classifying Stack Overflow posts tagged with `[nlp]` using machine learning and lexicon-based sentiment analysis.

---

## 📂 Project Structure

```
├── category_distribution.png       # Bar chart of NLP topic categories
├── confusion.png                   # Confusion matrix comparing VADER vs ML predictions
├── wordcloud.png                   # Word cloud from preprocessed text
├── sentiment_distribution1.png     # Sentiment distribution bar chart
├── stackoverflow_nlp_combined.zip  # Compressed dataset of 16,005 posts
├── NPL STACK OVERFLOW Report.pdf   # Final project report
```

---

## 📌 Objective

- **Collect** ~16,000 Stack Overflow posts related to NLP using the Stack Exchange API
- **Preprocess** the text using NLP techniques (lemmatization, stopword removal, etc.)
- **Categorize** posts into meaningful NLP subtopics
- **Analyze sentiment** using VADER and compare results with ML predictions
- **Visualize** insights through plots and charts

---

## 🧰 Tools and Libraries

- Python 3.10+
- pandas
- scikit-learn
- matplotlib
- seaborn
- nltk
- wordcloud
- vaderSentiment

---

## 📦 Installation

```bash
git clone https://github.com/gayathrikodakandla/nlp-stackoverflow-miniproject.git
cd nlp-stackoverflow-miniproject
pip install -r requirements.txt
```

> If the dataset is too large to push directly, use the `.zip` file and unzip locally:
```bash
unzip stackoverflow_nlp_combined.zip
```

---

## 📊 Dataset

- **Source**: [Stack Exchange API](https://api.stackexchange.com/)
- **Posts**: 16,005
- **Fields**: question ID, title, body, tags

---

## 🗂️ Categories Used

- `tokenization`
- `transformers`
- `ner`
- `language modeling`
- `text classification`
- `text generation`
- `translation`
- `question answering`
- `embedding`
- `other`

Each category was created using keyword-based rules and refined by evaluating sample posts.

---

## 📈 Results

- **ML Classification Accuracy**: 73.26%
- **VADER & ML Sentiment Agreement**: 82.4%
- **Sentiment Breakdown**: 77% Positive, 22% Negative, 1% Neutral

See `confusion.png` and `sentiment_distribution1.png` for visuals.

---

## 📄 Report

The full academic report outlining methodology, code, results, and reflections is available as:
- `NPL STACK OVERFLOW Report.pdf`

---

## 🔗 Citation

```
Gayathri Kodakandla. "Automated Text Classification of Stack Overflow NLP Posts." University of Adelaide, 2025.


