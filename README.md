# Fake News Detector

A simple **Machine Learning based Fake News Detection system** built using **Python and Scikit-learn**.
This project analyzes news text and predicts whether the news is **Real or Fake** using **TF-IDF Vectorization** and a **Logistic Regression classifier**.

---

## 📌 Project Overview

Fake news spreads quickly across the internet and social media platforms. This project demonstrates how **Natural Language Processing (NLP)** and **Machine Learning** can be used to classify news articles as real or fake.

The model is trained on a labeled dataset of news articles and then used to predict the authenticity of user-provided news text.

---

## ⚙️ Technologies Used

* Python
* Pandas
* Scikit-learn
* Natural Language Processing (NLP)

---

## 🧠 Machine Learning Pipeline

1. Load the news dataset
2. Split the dataset into training and testing data
3. Convert text data into numerical features using **TF-IDF Vectorization**
4. Train the model using **Logistic Regression**
5. Evaluate the model using **Accuracy Score**
6. Predict whether a news headline is real or fake

---

## 📂 Project Structure

```
Fake-News-Detector/
│
├── fake_news_detector.py
├── news_dataset.csv
└── README.md
```

---

## 🚀 Installation

1. Clone the repository

```bash
git clone https://github.com/your-username/fake-news-detector.git
```

2. Navigate to the project folder

```bash
cd fake-news-detector
```

3. Install required libraries

```bash
pip install pandas scikit-learn
```

---

## ▶️ Usage

Run the Python script:

```bash
python fake_news_detector.py
```

Then enter a news headline when prompted.

Example:

```
Enter a news headline:
Scientists confirm water found on Mars
```

Output:

```
This looks like REAL news
```

or

```
This looks like FAKE news
```

---

## 📊 Model Details

| Component         | Method Used                |
| ----------------- | -------------------------- |
| Text Processing   | TF-IDF Vectorizer          |
| Algorithm         | Logistic Regression        |
| Dataset Split     | 80% Training / 20% Testing |
| Evaluation Metric | Accuracy Score             |

---

## 📈 Possible Improvements

* Use a larger dataset
* Implement Deep Learning models (LSTM / BERT)
* Add a web interface using **Flask or Streamlit**
* Deploy as an API
* Add real-time news verification

---

## 👨‍💻 Author

Amrita , Priyanshi , Prince 
B.Tech ECE-DS , ME
SRM Institute of Science and Technology (Delhi NCR)


This project is open source and available under the **MIT License**.
