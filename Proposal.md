# Emotion Classification from Tweets

## Topic

For this project, I'm building a machine learning model that predicts the **emotion behind a tweet**. I'm using the [`mteb/emotion`](https://huggingface.co/datasets/mteb/emotion) dataset, which contains short English tweets labeled with one of six emotions: **joy**, **sadness**, **anger**, **fear**, **love**, and **surprise**.

The goal is to create a working emotion classifier using a straightforward and lightweight approach.

## What Makes This Project Different

Most projects I’ve seen around emotion detection use transformer-based models like BERT. While those are powerful, they can be a bit much for quick experiments or people who are just starting out.

Instead, I’ll be using a **traditional machine learning pipeline** — specifically:
- Preprocessing tweets
- Turning them into features using **TF-IDF**
- Training a **Logistic Regression** model
- Evaluating the results using accuracy, F1 score, and a confusion matrix

I want this to be simple, efficient, and easy to understand — something that doesn’t need a GPU to run, but still gives solid results.

## Live Site

🔗 [https://isjustabhi.github.io/Emotion-Classification-Tweets/](https://isjustabhi.github.io/Emotion-Classification-Tweets/)

The site is live and will include updates and links to my notebook as I make progress.
