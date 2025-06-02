# 🚀 Emotion & Sentiment Analysis using Large Language Models (LLMs)

This project showcases the use of transformer-based models — including encoder-only and full LLMs — to detect **emotions and sentiment** in text. It covers **multi-label classification**, **spam detection**, and comparison of model architectures, optimized for real-world NLP tasks.

> 🧠 **Built using PyTorch, Hugging Face Transformers**

## 💡 Problem Statement

Traditional sentiment analysis often oversimplifies text as positive, negative, or neutral. In reality, human emotions are complex and layered.
This project aims to build models that can:

* Accurately detect **multiple emotions** from a single input (e.g., "joy" + "trust")
* Work well on **noisy real-world text** like social media
* Distinguish between spam vs genuine emotional content

---

## 🧰 Tech Stack

| Category          | Tools Used                                     |
| ----------------- | ---------------------------------------------- |
| Language Models   | RoBERTa, BERT, LLaMA, Gemma (via Gemini API)   |
| Frameworks        | PyTorch, Hugging Face Transformers             |
| Other Tools       | Scikit-learn, BeautifulSoup, Matplotlib        |

---

## 📁 Key Modules

| Folder                       | Description                                                          |
| ---------------------------- | -------------------------------------------------------------------- |
| `EncoderOnly/`               | Multi-label classification using encoder-only models (e.g., RoBERTa) |
| `LLMs/`                      | LLM-based classification                         |
| `Multilabel_Classification/` | Focus on F1-macro optimization across 11 emotion labels              |
| `SpamDetection/`             | Identifies spam in emotionally ambiguous texts                       |
| `datafolder/`                | Sample datasets used for training and evaluation                     |

---

## ✅ Highlights & Results

* Achieved **F1-macro score of 61%** using RoBERTa on multi-label emotion data
* Fine-tuned models with **imbalanced data handling** (class weights, oversampling)
* Compared traditional classifiers (LogReg, LSTM) with transformer-based models


## 👩‍💻 My Role

* Designed and implemented the full ML pipeline for encoder-only models
* Handled data preprocessing, label binarization, and model tuning
* Conducted performance evaluation using precision, recall, and F1-macro

