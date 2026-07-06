# Spam Email Classifier 📧

A machine learning project that classifies SMS messages as **Spam** or **Ham (Not Spam)** using Natural Language Processing (NLP) and a Naive Bayes classifier. Achieved **97.31% accuracy** on the UCI SMS Spam Collection dataset.

---

## 📊 Results

| Metric | Score |
|--------|-------|
| Accuracy | 97.31% |
| Precision (Spam) | 97% |
| Recall (Spam) | 92% |
| F1-Score (Spam) | 94% |

---

## 🛠️ Tech Stack

- **Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, WordCloud
- **NLP:** TF-IDF Vectorization, Text Preprocessing (regex, lowercasing, punctuation removal)
- **Model:** Multinomial Naive Bayes
- **Environment:** Jupyter Notebook

---

## 📁 Dataset

**UCI SMS Spam Collection Dataset**
- 5,572 SMS messages labeled as spam or ham
- Source: [Kaggle](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)

---

## 🔍 Project Workflow

1. **Data Loading & Exploration** — loaded dataset, checked class distribution (spam vs ham)
2. **Text Preprocessing** — lowercased text, removed numbers, punctuation, and extra whitespace
3. **Feature Extraction** — converted text to numerical features using TF-IDF (3000 features)
4. **Model Training** — trained Multinomial Naive Bayes on 80% of the data
5. **Evaluation** — tested on 20% holdout set; generated classification report and confusion matrix
6. **Visualization** — word clouds for most common spam and ham words
7. **Prediction** — custom function to classify any new message with confidence score

---

## 📈 Visualizations

- Spam vs Ham class distribution bar chart
- Confusion matrix heatmap
- Word clouds for spam and ham messages

---

## 🚀 How to Run

1. Clone the repository
```bash
git clone https://github.com/Akshay0721/spam-email-classifier.git
cd spam-email-classifier
```

2. Install dependencies
```bash
pip install pandas numpy scikit-learn matplotlib seaborn wordcloud
```

3. Launch Jupyter Notebook
```bash
jupyter notebook spam_classifier.ipynb
```

4. Run all cells in order

---

## 💡 Sample Predictions

```
Message: "Congratulations! You've won a free iPhone. Click here to claim now!"
Prediction: 🚨 SPAM — Confidence: 94.04%

Message: "Hey, are we still meeting for lunch tomorrow?"
Prediction: ✅ HAM — Confidence: 99.67%
```

---

## 👤 Author

**Akshay Kumar Pillalamarri**
- 📧 apillala@uab.edu
- 💼 [LinkedIn](https://www.linkedin.com/in/akshaykumar-pillalamarri-60a9311a9/)
- 🐙 [GitHub](https://github.com/Akshay0721)
