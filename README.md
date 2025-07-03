# Spam_Email_Classification



This project is a machine learning-based spam email classifier that identifies whether a given message is Spam or Not Spam (Ham) using Natural Language Processing (NLP). The model is trained on real-world datasets and can be used via CLI, GUI, or web interface.

---

## Problem Statement

Spam emails and messages not only clutter inboxes but can also be dangerous (phishing, scams). Automating spam detection helps reduce risks and improves user productivity.

---

## Objectives

- Preprocess and vectorize email/message text.
- Build a classifier to detect spam.
- Provide user-friendly interfaces for prediction.
- Save and reuse the trained model for future predictions.

---

## Project Structure
Spam_Email_Classification/
├──spam.csv # Dataset
├── spam_model.pkl# Trained model
├── spam_classifier.ipynb
├── predict.py
├── gui_predict.py # GUI application using Tkinter
└── README.md # This file

Dataset

- **Name**: SMS Spam Collection Dataset  
- **Source**: [Kaggle Link](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)  
- Contains 5,574 SMS messages tagged as `ham` or `spam`.

Tech Stack

- Python 3.x
- pandas, scikit-learn
- NLTK
- Tkinter (for GUI)
- Jupyter Notebook

 Sample Predictions
Input: Congratulations! You've won a free iPhone. Click now!
Output: Spam 

Input: Meeting rescheduled to 3 PM. Please confirm.
Output: Not Spam 


