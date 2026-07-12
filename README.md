# Live Sentiment & Emotion Analysis Web Application

An interactive web application built with Python and Flask that utilizes advanced Natural Language Processing (NLP) models to analyze the sentiment and underlying human emotions of text data in real-time.

## Features
* **General Sentiment Classification:** Analyzes text data to classify it instantly as Positive, Negative, or Neutral using lexicon-based evaluation.
* **Fine-Grained Emotion Detection:** Uses deep learning transformer models to detect specific human emotions such as joy, sadness, anger, fear, and surprise.
* **Interactive Browser GUI:** A clean, user-friendly web interface where anyone can paste text streams (like customer feedback, reviews, or social updates) and see analysis results immediately.

---

## Tech Stack & Architecture
* **Backend Framework:** Flask (Python Web Server)
* **Frontend UI:** Responsive HTML5 & CSS3
* **Sentiment Engine:** NLTK (VADER Sentiment Intensity Analyzer)
* **Emotion Model:** Hugging Face Transformers (`distilroberta-base` fine-tuned for emotion detection)
* **Core Libraries:** `pandas`, `torch`, `openpyxl`

---

## Installation & Setup

### 1. Install Dependencies
Run the following command in your terminal or inside your Jupyter Notebook environment to install all required packages:

```bash
pip install flask pandas nltk transformers torch openpyxl



https://github.com/user-attachments/assets/3f5554e2-479a-4014-b1ba-135333143872



