# Sentiment Analysis Web App

A simple Flask-based web application that performs sentiment analysis on user-inputted text using a Naive Bayes model trained with scikit-learn.

## Features

- Predicts whether a sentence is **positive** or **negative**
- Trained on a small custom dataset
- Uses `scikit-learn` for machine learning
- Built with Flask as a lightweight web framework
- Easy to expand or deploy

##  Model

- Vectorizer: `CountVectorizer`
- Classifier: `Multinomial Naive Bayes`
- Trained on basic sample sentences (can be replaced with larger datasets)

---

## Installation

```bash
git clone https://github.com/yourusername/sentiment-analysis-app.git
cd sentiment-analysis-app
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
pip install -r requirements.txt
