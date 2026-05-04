# AI-Based Subjective Exam Evaluation

## 📌 Overview
This project focuses on automating the evaluation of subjective (descriptive) answers using Artificial Intelligence and Natural Language Processing (NLP). 

Traditional evaluation of subjective answers is time-consuming and inconsistent due to human bias. This system aims to provide a faster, more consistent, and scalable evaluation method.

---

## 🎯 Objectives
- Automate grading of subjective answers
- Reduce human bias in evaluation
- Provide consistent and accurate scoring
- Improve evaluation efficiency

---

## 🧠 How It Works
The system evaluates answers based on multiple parameters:

- **Keyword Matching** – Checks presence of important terms
- **Semantic Similarity** – Compares student answer with model answer
- **Grammar Checking** – Evaluates language correctness
- **Content Relevance** – Ensures answer matches the question

The final score is generated based on these combined factors.

---

## 🛠️ Technologies Used
- Python
- Natural Language Processing (NLP)
- Machine Learning
- Libraries:
  - NLTK / SpaCy
  - Scikit-learn
  - FuzzyWuzzy (for similarity)
  - Text processing tools

---

## ⚙️ Features
- Automatic answer evaluation
- Score generation
- Comparison with model answers
- Basic plagiarism detection (optional)
- User-friendly interface (if GUI/web included)

---

## 📂 Project Structure

├── dataset/
├── models/
├── utils/
├── main.py
├── evaluation.py
├── requirements.txt
└── README.md


---

## 🚀 Installation & Setup

1. Clone the repository:
```bash
git clone https://github.com/srujanredy01/AI-Based-Subjective-Exam-Evaluation.git
cd AI-Based-Subjective-Exam-Evaluation
Install dependencies:
pip install -r requirements.txt
Run the project:
python main.py
