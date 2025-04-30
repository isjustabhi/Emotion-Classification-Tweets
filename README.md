# Emotion-Classification-Tweets
Emotion Classification from Tweets Using TF-IDF and Logistic Regression

# 🧠 Emotion Classification in Tweets 

This project focuses on building a **multi-class emotion classifier** for English-language tweets using a **lightweight, interpretable NLP pipeline**.

Instead of relying on deep learning or transformer-based models, this experiment uses **TF-IDF vectorization** and **Logistic Regression** to predict the emotion expressed in a tweet. It's simple, fast, and surprisingly effective — showing that classical methods still have strong value in NLP.

---

## 📌 Project Goal

- Detect the **emotion** behind a tweet (joy, sadness, anger, fear, love, or surprise)
- Use traditional NLP tools to keep the model **interpretable and low-resource**
- Serve as a **baseline** for future experimentation with deep learning

---

## 🗃️ Dataset

We use the [`mteb/emotion`](https://huggingface.co/datasets/mteb/emotion) dataset from Hugging Face, which includes:

- **~20,000 tweets**
- **Six emotion labels**: `joy`, `sadness`, `anger`, `fear`, `love`, `surprise`
- Pre-split into **train**, **validation**, and **test** sets

---

## 🔧 Methodology

1. **Preprocessing**  
   Lowercasing, punctuation and stopword removal

2. **Feature Engineering**  
   Text → TF-IDF representation

3. **Model Training**  
   Logistic Regression classifier

4. **Evaluation**  
   Accuracy, F1-score, and a confusion matrix

5. **Visualization**  
   Emotion label distribution and confusion matrix heatmap

---

## 📊 Sample Confusion Matrix

![Confusion Matrix]![confusion_matrix_sample](https://github.com/user-attachments/assets/7cf3760e-ce12-4562-9153-df107e3ac41c)


---

## ✅ Key Takeaways

- Achieved strong performance using only classical tools
- Model is fast to train, runs on CPUs, and is easy to understand
- Demonstrates that **traditional NLP methods are still useful and relevant**
- A solid starting point for more advanced models like BERT or RoBERTa

---

## 🛠️ How to Run

1. **Clone the Repository**  
```bash
git clone https://github.com/isjustabhi/Emotion-Classification-Tweets.git
cd Emotion-Classification-Tweets
