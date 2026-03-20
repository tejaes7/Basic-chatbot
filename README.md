# 🤖 Chatbot using NLP and Machine Learning

## 📌 Overview

In this project, I built an intent-based chatbot using Python, Natural Language Processing (NLP), and Machine Learning. The chatbot can understand user input, classify it into predefined categories (intents), and respond accordingly.

This project helped me understand how real-world conversational systems are designed using data preprocessing, feature extraction, and classification models.

---

## 🚀 Features

* Text preprocessing using NLP techniques
* Intent classification using Machine Learning
* TF-IDF vectorization for text representation
* Interactive chatbot interface
* Supports multiple user queries with varied patterns
* Improved understanding using n-grams

---

## 🧠 Tech Stack

* Python
* NLTK
* Scikit-learn
* JSON (for dataset)

---

## 📂 Project Structure

```
Chatbot/
│
├── intents.json        # Dataset (intents, patterns, responses)
├── chatbot.ipynb       # Main implementation
├── model.pkl           # Saved ML model
├── vectorizer.pkl      # Saved TF-IDF vectorizer
└── README.md
```

---

## ⚙️ How It Works

### 1. Data Preparation

* Created a custom dataset of intents with multiple patterns and responses.

### 2. Text Preprocessing

* Converted text to lowercase
* Removed punctuation
* Tokenized sentences
* Applied stemming

### 3. Feature Extraction

* Used TF-IDF vectorization to convert text into numerical features
* Applied n-grams to capture word combinations

### 4. Model Training

* Trained a Logistic Regression model to classify user input into intents

### 5. Chatbot Logic

* Takes user input
* Preprocesses it
* Converts it into vector form
* Predicts intent
* Returns a random response from that intent

---

## 📊 Example

```
You: hello  
Bot: Hi there!

You: tell me a joke  
Bot: Why did the programmer quit his job? Because he didn't get arrays 😄
```

---

## ⚠️ Limitations

* Works only with predefined intents
* Limited understanding of complex or unseen queries
* No deep contextual awareness

---

## 🔥 Future Improvements

* Add context-aware conversation (memory)
* Use advanced NLP models like BERT or GPT
* Deploy as a web app using Flask or Streamlit
* Expand dataset for better accuracy

---

## 💡 What I Learned

* NLP preprocessing techniques
* Text vectorization (TF-IDF)
* Machine learning for classification
* How chatbots work internally
* Importance of dataset quality

---

## 📌 Conclusion

This project is a foundational step into building intelligent conversational systems. It demonstrates how machine learning and NLP can be combined to create interactive applications.

---

⭐ If you found this project useful, feel free to star the repo!
