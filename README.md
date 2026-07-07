# 📰 Fake News Detection using Recurrent Neural Network (RNN)

## 📌 Project Overview

Fake news has become one of the biggest challenges in today's digital world, spreading misinformation rapidly through online platforms. This project develops a **Fake News Detection System** using **Natural Language Processing (NLP)** and a **Recurrent Neural Network (RNN)** to automatically classify news articles as **Fake** or **Real**.

The model processes textual news data through several NLP preprocessing techniques before training an RNN capable of understanding sequential patterns within text. The project demonstrates the complete machine learning workflow, including data preprocessing, exploratory data analysis, model development, evaluation, and prediction.

---

## 🎯 Objectives

- Detect fake news articles using Deep Learning.
- Perform comprehensive NLP preprocessing on textual data.
- Train an RNN model for binary text classification.
- Evaluate model performance using multiple metrics.
- Predict whether unseen news articles are Fake or Real.

---

## 📂 Dataset

The project uses two publicly available datasets:

- **Fake.csv** – Contains fake news articles.
- **True.csv** – Contains genuine news articles.

Each dataset contains attributes such as:

- Title
- Text
- Subject
- Date

The datasets are merged and labeled before model training.

| Label | Description |
|--------|-------------|
| 0 | Fake News |
| 1 | Real News |

---

## 🛠 Technologies Used

### Programming Language
- Python

### Libraries

- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- NLTK

---

## 📊 Project Workflow

```
Dataset Collection
        │
        ▼
Data Cleaning
        │
        ▼
Text Preprocessing
(Case Folding, Tokenization,
Stopword Removal, Lemmatization)
        │
        ▼
Text Vectorization
(Tokenization & Padding)
        │
        ▼
Train-Test Split
        │
        ▼
RNN Model Development
        │
        ▼
Model Training
        │
        ▼
Model Evaluation
        │
        ▼
Prediction on New News Articles
```

---

## 🧹 Text Preprocessing

The following preprocessing techniques were applied:

- Removal of unnecessary columns
- Handling missing values
- Lowercase conversion
- Removal of punctuation
- Removal of special characters
- Removal of numbers
- Tokenization
- Stopword removal
- Lemmatization
- Text padding

These steps reduce noise and improve the quality of textual features used by the RNN.

---

## 🧠 Model Architecture

The model consists of:

- Embedding Layer
- Simple RNN Layer
- Dense Hidden Layer
- Sigmoid Output Layer

The sigmoid activation function produces a probability score indicating whether a news article is fake or real.

---

## 📈 Model Evaluation

The trained model is evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Classification Report

Training and validation accuracy/loss curves are also used to monitor model performance.

---

## 📁 Project Structure

```
Fake-News-RNN/
│
├── Fake.csv
├── True.csv
├── RNN_Fake_News_Project.ipynb
├── README.md
└── requirements.txt
```

---

## 🚀 Installation

Clone the repository

```bash
git clone https://github.com/yourusername/Fake-News-RNN.git
```

Navigate into the project directory

```bash
cd Fake-News-RNN
```

Install the required packages

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

Open

```
RNN_Fake_News_Project.ipynb
```

---

## ▶️ How to Run

1. Download the datasets.
2. Place **Fake.csv** and **True.csv** in the project folder.
3. Open the notebook.
4. Run all cells sequentially.
5. Train the RNN model.
6. Test the model using custom news articles.

---

## 📌 Features

- End-to-end NLP pipeline
- Deep Learning based Fake News Detection
- RNN architecture
- Text preprocessing
- Data visualization
- Performance evaluation
- Prediction on custom news articles

---

## 📚 Learning Outcomes

Through this project, the following concepts were implemented:

- Natural Language Processing (NLP)
- Deep Learning
- Recurrent Neural Networks (RNN)
- Text Classification
- Data Preprocessing
- Model Evaluation
- Binary Classification
- TensorFlow/Keras

---

## 🔮 Future Enhancements

- Replace Simple RNN with LSTM or GRU
- Integrate BERT for contextual embeddings
- Hyperparameter tuning
- Deploy the model using Streamlit or Flask
- Create a REST API
- Dockerize the application
- Cloud deployment using AWS or Azure

---
