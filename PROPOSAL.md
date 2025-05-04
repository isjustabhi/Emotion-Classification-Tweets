# Project Proposal – Option 2: Modeling Experiment

## Title  
**Emotion Classification in Tweets Using Traditional NLP Techniques**

## Project Motivation
Emotions expressed on social media platforms, especially Twitter, can offer valuable insight into public opinion, mental health trends, and user engagement patterns. Understanding these emotions in real time can support organizations across sectors  from marketing teams looking to gauge campaign impact, to researchers studying societal sentiment.

While many modern NLP models rely on deep learning architectures, this project explores the effectiveness of traditional approaches using classical machine learning and text vectorization methods to detect emotions from tweets.

## Objective  

The aim of this project is to build a lightweight NLP pipeline that:
- Identifies the dominant **emotion** in a given tweet (e.g., joy, sadness, anger)  
- Evaluates the performance of classical models on multi-class emotion classification  
- Explores the distribution of emotions across the dataset  
- Provides a clear, interpretable baseline that could later be extended to more complex models

This experiment will demonstrate that traditional methods can still be effective for real-world NLP tasks, especially when computational resources are limited.

## Dataset  
- [mteb/emotion on Hugging Face](https://huggingface.co/datasets/mteb/emotion)

The dataset includes short English-language tweets labeled with one of six emotion categories:
- **joy**
- **sadness**
- **anger**
- **fear**
- **love**
- **surprise**

It includes predefined splits for training, validation, and testing.

## Modeling Approach  

The project will follow these stages:

1. **Data Preprocessing and Exploration**  
   - Lowercasing, punctuation and stopword removal  
   - Basic visualization of emotion frequency  
   - Handling class imbalance if needed

2. **Feature Engineering**  
   - Convert tweets into numerical features using **TF-IDF vectorization**

3. **Model Training and Evaluation**  
   - Train a **Logistic Regression** classifier for multi-class prediction  
   - Evaluate using **accuracy**, **F1 score**, and **confusion matrix**  
   - Compare performance across classes

4. **Visualization and Interpretation**  
   - Plot confusion matrix and emotion distribution  
   - Identify top features (words) contributing to each emotion

This approach is designed to be efficient, reproducible, and easy to understand.

---

- 📁 **Repo link**: [Emotion-Classification-Tweets](https://github.com/isjustabhi/Emotion-Classification-Tweets)
- 📄 **Proposal**: [PROPOSAL.md](https://github.com/isjustabhi/Emotion-Classification-Tweets/blob/main/Proposal.md)

