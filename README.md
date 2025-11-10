# 🧠 Employee Sentiment Analysis

This project analyzes internal employee messages to identify sentiment trends, understand team morale, and detect early signs of negative engagement using Natural Language Processing (NLP).

---

## 📋 Overview

The goal of this project is to study how employees feel based on their communication patterns.
A RoBERTa transformer model was used to classify each message as **Positive**, **Neutral**, or **Negative**.
The insights can help HR teams improve workplace satisfaction and monitor employee well-being.

---

## 🚀 Features

* **Sentiment Classification**: Uses a pre-trained `cardiffnlp/twitter-roberta-base-sentiment-latest` model.
* **Data Visualization**: Shows distribution of sentiments using Seaborn and Matplotlib.
* **Automated Processing**: Reads messages from a CSV dataset and performs end-to-end sentiment labeling.
* **Insight Reporting**: Summarizes positive, negative, and neutral communication trends.

---

## 🧰 Tech Stack

| Component            | Tool/Library                                                 |
| -------------------- | ------------------------------------------------------------ |
| Programming Language | Python 3.x                                                   |
| NLP Model            | RoBERTa (`cardiffnlp/twitter-roberta-base-sentiment-latest`) |
| Data Analysis        | pandas, numpy                                                |
| Visualization        | matplotlib, seaborn                                          |
| Environment          | Google Colab / Jupyter Notebook                              |

---

## 📂 Repository Structure

```
employee-sentiment-analysis-by-ruchita/
├── employee_messages.csv               # Dataset
├── employee_sentiment_results.csv      # Output after analysis
├── employee_sentiment_analysis.ipynb   # Main Notebook
├── README.md                           # Project documentation
```

---

## 📈 Example Results

* **Positive**: 35%
* **Neutral**: 50%
* **Negative**: 15%

The sentiment distribution graph provides an overview of how employees feel during a given period.

---

## 💡 Key Takeaways

* Helps HR identify satisfaction levels among employees.
* Detects early warning signs like rising negative sentiment.
* Useful for employee engagement and performance improvement.

---

## 🧭 Future Enhancements

* Add time-series trend analysis by department or project.
* Integrate dashboard (Streamlit or Flask).
* Include emotion detection (anger, joy, sadness, etc.) beyond basic sentiment.

---

## 👩‍💻 Author

**Borpatla Ruchita Nandini**
B.Tech in Artificial Intelligence and Data Science
Shadan Women's College of Engineering and Technology
GitHub: [@ruchitanandini](https://github.com/ruchitanandini)
