# 🎬 IMDB Movie Review Sentiment Analyzer

This project is an **End-to-End Sentiment Analysis Pipeline** built using **PyTorch (Deep Learning)** and deployed through **Streamlit** as an interactive web app.  
The model classifies movie reviews from the IMDB dataset into **Positive** or **Negative** sentiments.

---

## 📖 Table of Contents
1. [Overview](#overview)
2. [Features](#features)
3. [Architecture](#architecture)
4. [Dataset](#dataset)
5. [Installation & Usage](#installation--usage)
6. [Demo](#demo)
7. [Results](#results)
8. [Tech Stack](#tech-stack)
9. [Future Enhancements](#future-enhancements)
---

## **Overview**

Movie reviews are an excellent benchmark for Natural Language Processing tasks.  
This project:
- Preprocesses text data (cleaning, tokenization, encoding)
- Trains an **LSTM neural network** from scratch using **PyTorch**
- Deploys an interactive web application using **Streamlit**

The web app lets users input any movie review and instantly get:
- **Sentiment classification (Positive/Negative)**
- **Confidence score displayed as stars**

---

## **Features**

- 🧠 **Deep Learning Model:** LSTM-based architecture
- 🗃 **Dataset:** IMDB 50,000 labeled reviews
- 🖥 **Interactive Streamlit UI** with:
  - Text input for user reviews
  - Result display with confidence scores
  - Custom background and styled UI
- ⭐ **Confidence visualization using star ratings**
- 🏆 **Model accuracy achieved: ~87%**

---

## Tech Stack
- **Python 3.9+**
- **PyTorch** for deep learning
- **Streamlit** for the interactive web app
- **Pandas, NumPy, scikit-learn** for data handling

## **Architecture**

**Steps:**
1. Data Preprocessing
2. Vocabulary Encoding
3. Train/Test Split
4. Model Training (LSTM)
5. Save model (`imdb_lstm_model.pth`)
6. Deploy on Streamlit

**Model Summary:**
- Embedding Layer
- LSTM Layer
- Dropout (0.5)
- Fully Connected Layer
- Sigmoid Output

---

## **Dataset**

Dataset used:  
[IMDB 50K Movie Reviews](https://ai.stanford.edu/~amaas/data/sentiment/)  
- 25,000 labeled reviews for training
- 25,000 labeled reviews for testing
- Balanced dataset (Positive & Negative reviews)

---

## **Output**

<img width="1919" height="960" alt="image" src="https://github.com/user-attachments/assets/a8a963e6-04f4-4db5-bbd8-ae84ad42689b" />
<img width="1916" height="958" alt="image" src="https://github.com/user-attachments/assets/8a510c01-43c9-4592-972a-725e48f64c88" />


## **Installation & Usage**

### 1. Clone the repository:
```bash
git clone https://github.com/your-username/IMDB-Sentiment-Analyzer.git
cd IMDB-Sentiment-Analyzer
