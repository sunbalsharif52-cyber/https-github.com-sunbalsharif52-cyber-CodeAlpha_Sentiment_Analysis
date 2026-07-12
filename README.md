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
* **Core Libraries:** pandas, torch, openpyxl

---

## Installation & Setup

### 1. Install Dependencies
Run the following command in your terminal or inside your Jupyter Notebook environment to install all required packages:

**Command:** pip install flask pandas nltk transformers torch openpyxl

---

### 🎥 Project Demo Video

You can watch the live working video of this project. Click the link below to open the demo video to clearly see the complete application interface:

[Click here to watch the project demo video](https://github.com/user-attachments/assets/3f5554e2-479a-4014-b1ba-135333143872)

---

### 2. Running the Application via Jupyter Notebook
1. Open your project notebook file (.ipynb).
2. Run the code cells sequentially from top to bottom.
3. The final cell will start a local web server and output a network link: [http://127.0.0.1:5000](http://127.0.0.1:5000)
4. Click the link or open it manually in your web browser to access the live application.

---

## Usage Guide
1. Launch the application in your browser using the local host link.
2. Enter or paste any product review, social comment, or article headline into the text area.
3. Click the **"Analyze Sentiment"** button.
4. The application will instantly display the calculated general sentiment category alongside the specific primary emotion identified by the AI system.

---

## License
This project is open-source and available under the MIT License.
