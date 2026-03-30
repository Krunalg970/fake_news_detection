# 📰 Fake News Detection System

A Machine Learning project that detects whether a news article is **Fake** or **Real** using **Natural Language Processing (NLP)** and **Logistic Regression**.

---

## 🚀 Project Overview

The **Fake News Detection System** is a Machine Learning-based project designed to identify fake news articles automatically. This system uses Natural Language Processing techniques to analyze text data and classify news as **Fake** or **Real**.

This project demonstrates the complete machine learning workflow including data preprocessing, feature extraction, model training, evaluation, and prediction.

---

## 🛠️ Technologies Used

* Python
* NumPy
* Pandas
* Scikit-learn
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## 📂 Project Structure

```
Fake-News-Detection/
│
├── fake_news_detection.ipynb   # Main notebook
├── train.csv                   # Training dataset
├── test.csv                    # Testing dataset
└── README.md                   # Project documentation
```

---

## 📊 Dataset

The dataset contains news articles labeled as:

* **Fake (0)** → Fake News
* **Real (1)** → Real News

Dataset features:

* Title
* Author
* Text
* Label

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/fake-news-detection.git
```

Navigate to project folder:

```bash
cd fake-news-detection
```

Install dependencies:

```bash
pip install numpy pandas scikit-learn matplotlib seaborn
```

---

## ▶️ How to Run

Open Jupyter Notebook:

```bash
jupyter notebook
```

Open the notebook:

```
fake_news_detection.ipynb
```

Run all cells.

---

## 🧠 Model Workflow

### 1. Import Dependencies

* NumPy
* Pandas
* Scikit-learn

### 2. Data Preprocessing

* Load dataset
* Handle missing values
* Clean text data

### 3. Feature Extraction

* Convert text data using **TF-IDF Vectorizer**

### 4. Model Training

* Logistic Regression Model

### 5. Model Evaluation

* Accuracy Score
* Training & Testing Accuracy

### 6. Prediction System

* Input news text
* Model predicts Fake or Real

---

## 📈 Model Accuracy

* Training Accuracy: ~98% (approx)
* Testing Accuracy: ~96% (approx)

*(Accuracy may vary depending on dataset)*

---

## 💡 Example Prediction

```python
news = ["Breaking: Government announces new policy today"]

prediction = model.predict(news)

if prediction[0] == 0:
    print("Fake News")
else:
    print("Real News")
```

---

## 🎯 Features

✅ Fake News Detection
✅ Machine Learning Model
✅ NLP Text Processing
✅ Logistic Regression
✅ Easy to Understand

---

## 📌 Future Improvements

* Add Deep Learning Model
* Create Web App using Streamlit
* Deploy Model
* Add API Support

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repository and submit pull requests.

---

## 📜 License

This project is open-source and available under the **MIT License**.

---

## 👨‍💻 Author

**Krunal Goswami**

---

⭐ If you like this project, don't forget to give it a star on GitHub!
