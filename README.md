# 🧠 Emotion Detection from Text (NLP + Machine Learning)

Emotion Detection from Text is a **Natural Language Processing (NLP) project** that classifies emotions from textual data using machine learning techniques.

The system processes raw text, applies cleaning and feature extraction, and predicts emotions such as **sadness, anger, love, etc.** with high accuracy.

## 🎯 Problem Statement

The goal of this project is to build a model that can automatically **detect emotions from text data**.
This helps in applications like:

* Sentiment analysis
* Chatbots
* Social media monitoring

## 📂 Dataset

* Text dataset with labeled emotions
* Each record contains:

  * Text input
  * Corresponding emotion label

✔ No missing values found 

## 🧹 Data Preprocessing

Performed multiple NLP cleaning steps:

* Converted text to lowercase
* Removed punctuation
* Removed numbers
* Removed emojis
* Removed stopwords using NLTK
* Tokenized and cleaned text

👉 Example:
Before:

```
i can go from feeling so hopeless to so damned hopeful...
```

After:

```
go feeling hopeless damned hopeful around someone cares awake
```

## 🔢 Feature Engineering

Used two techniques:

### 1. Bag of Words (BoW)

* Implemented using CountVectorizer

### 2. TF-IDF

* Implemented using TfidfVectorizer
* Captures importance of words

## 🤖 Model Building

### Models Used:

* Multinomial Naive Bayes
* Logistic Regression

## 📊 Model Performance

| Model               | Technique    | Accuracy   |
| ------------------- | ------------ | ---------- |
| Naive Bayes         | Bag of Words | **76.8%**  |
| Naive Bayes         | TF-IDF       | **66.0%**  |
| Logistic Regression | TF-IDF       | **86.28%** |

👉 Best Model: **Logistic Regression with TF-IDF** 

## 🛠️ Tech Stack

**Programming →** Python
**Libraries →**
* Pandas
* NumPy
* Scikit-learn
* NLTK

## ⚙️ How It Works

📥 Input Text
→ 🧹 Text Cleaning (NLP preprocessing)
→ 🔢 Feature Extraction (BoW / TF-IDF)
→ 🤖 Machine Learning Model
→ 😊 Predicted Emotion


## ⚙️ How to Run

git clone https://github.com/ankitkumar8558011-alt/Emotion-Detection-from-Text-using-NLP-and-ML.git

python -m venv venv
venv\Scripts\activate   # Windows

pip install -r requirements.txt
python main.py

## 📊 Output

* Predicted emotion for given text
* Accuracy comparison between models
* Cleaned and processed dataset

## ⭐ Key Highlights

🔥 End-to-end NLP pipeline (cleaning → vectorization → modeling)
🔥 Multiple preprocessing steps (important skill)
🔥 Model comparison (BoW vs TF-IDF)
🔥 Achieved **86% accuracy** (strong result)
🔥 Real-world use case

## 👨‍💻 Author

👤 Name - Ankit Kumar

## ⭐ Support

If you like this project, give it a ⭐ on GitHub
