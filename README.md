# Live Sentiment & Emotion Analysis Web Application

An interactive web application built with Python and Flask that utilizes advanced Natural Language Processing (NLP) models to analyze the sentiment and underlying human emotions of text data in real-time.

## Features
* **General Sentiment Classification:** Analyzes text data to classify it instantly as Positive, Negative, or Neutral using lexicon-based evaluation.
* **Fine-Grained Emotion Detection:** Uses deep learning transformer models to detect specific human emotions such as joy, sadness, anger, fear, and surprise.
* **Interactive Browser GUI:** A clean, user-friendly web interface where anyone can paste text streams (like customer feedback, reviews, or social updates) and see analysis results immediately.
* **Data Insights:** Designed to process textual patterns to understand public opinion and inform product development or marketing trends.

---

## 📂 Dataset Information
Due to GitHub's file size limitations, the complete raw dataset (`Reviews.csv`) used for training and evaluating this system is hosted externally. 

* **Dataset Description:** A large-scale collection of customer product reviews and text streams, perfect for training robust NLP engines.
* **Download Link:** [Click here to download the complete Reviews.csv dataset](https://drive.google.com/file/d/17j0UuB86w6XN2xuXGxN5mJPVeBKViKhF/view?usp=drive_link) *(Note: Please place the downloaded file in the root directory before running the project locally).*

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
