# User Response-Based Fake News Detection on Social Media

This repository contains the codebase and experimental setup for our work on **fake news detection** using **user reactions on social media** posts. This approach is based on our paper titled _"User Response-Based Fake News Detection on Social Media"_, which investigates how users’ textual comments and emotional reactions can be leveraged to identify misinformation.

---

##  Abstract

Social media has become a dominant platform for mass communication and information sharing. Its interactive features—such as likes, shares, and comments—allow rapid propagation of content, but also expose users to unverified and potentially misleading information due to the lack of editorial oversight. In this work, we propose a method to detect fake news by analyzing user responses to social media posts. We extract textual features from user comments using Bag-of-Words and TF-IDF techniques, and incorporate categorical emotion responses as visual features. Our experimental results, based on models such as Random Forest, Logistic Regression, and XGBoost, show a precision of **0.97**, a recall of **0.99**, and an F1-score of **0.98**, significantly outperforming baseline methods.

---

## Introduction

### Motivation
The unregulated nature of social media platforms allows misinformation to spread widely and rapidly. Fake news can have severe consequences—misleading the public, influencing political opinions, or endangering public health.

### Problem Statement
Unlike traditional news media, social media lacks editorial controls and fact-checking processes. This creates a critical need for robust, data-driven methods to detect fake content effectively.

### Our Approach
We present a fake news detection framework that leverages **user reactions**:
- **Textual Comments** – what users write in response to a post.
- **Visual Emotion Responses** – affective cues such as likes, love, anger, etc.

These signals are used to train models that can predict whether a post is **fake** or **real**.

---

##  Methodology

We explore the effectiveness of **user reaction-based features** in detecting fake news. Our method consists of:

1. **Textual Feature Extraction**:
   - Using a Bag-of-Words model and **TF-IDF vectorization** on user comments.
   
2. **Emotion Feature Representation**:
   - Mapping **categorical emotion responses** (e.g., Like, Love, Sad, Angry) to features reflecting public sentiment.

3. **Classification Models**:
   - Experiments were conducted using multiple classifiers:
     - **Random Forest**
     - **Logistic Regression**
     - **XGBoost**
     - Others (for comparison)

---

##  Dataset: COVIDFake-EmoReact 2021

We use the **Fake-EmoReact 2021** dataset, released as part of the **SocialNLP 2021** shared task (in conjunction with NAACL 2021). This dataset enables analysis of fake news based on how users respond both textually and emotionally.

### Dataset Features

- **Social Media Posts**: Related to COVID-19.
- **User Reactions**:
  - Textual comments.
  - Emotion annotations (e.g., joy, sadness, anger).
- **Labels**: Each post is labeled as **Fake** or **Real**, based on fact-checking.

### Use Cases

- Fake news detection.
- Emotion and sentiment analysis.
- Multi-modal learning (text + emotion).
- Behavioral studies of misinformation.

### Official Website & Resources

- [COVIDFake-EmoReact 2021 – Shared Task](https://sites.google.com/view/covidfake-emoreact-2021/)

---

##  Repository includes  Structure
├── data/ # Dataset files accecable from [COVIDFake-EmoReact 2021 – Shared Task](https://sites.google.com/view/covidfake-emoreact-2021/)
├── src/ # Source code for model training and preprocessing
├── results/
├── main.py 
├── requirements.txt 
├── README.md 
