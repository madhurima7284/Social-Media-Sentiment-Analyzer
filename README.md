Social Media Sentiment Analyzer
🚀 Project Overview

The Social Media Sentiment Analyzer is a Machine Learning and Natural Language Processing (NLP) project that predicts whether a social media post expresses positive or negative sentiment.

This system analyzes textual data from social media platforms and classifies user opinions automatically using a trained machine learning model.

🎯 Objective

Analyze social media text data

Perform text preprocessing and cleaning

Apply NLP techniques

Train a sentiment classification model

Predict sentiment of new user input

🧠 Technologies Used

Python

Machine Learning

Natural Language Processing (NLP)

Scikit-learn

Pandas

NumPy

NLTK

Google Colab

📂 Dataset

Dataset used:

Twitter Sentiment Dataset (1.6 Million Tweets)

Dataset contains:

Tweet text

Sentiment label (Positive / Negative)

⚙️ Project Workflow
1️⃣ Data Collection

Loaded Twitter dataset using Pandas.

2️⃣ Data Preprocessing

Removed special characters

Converted text to lowercase

Removed stopwords

Applied stemming

3️⃣ Feature Extraction

Converted text data into numerical format using:

TF-IDF Vectorization

4️⃣ Model Training

Used:

Logistic Regression Classifier

5️⃣ Model Evaluation

Measured model accuracy using training and testing datasets.

6️⃣ Prediction System

Created a function to predict sentiment for custom input text.

Example:

predict_sentiment("I hate this post")
Output → NEGATIVE TWEET


▶️ How to Run the Project
Step 1: Clone Repository
git clone https://github.com/madhurima7284/Social-Media-Sentiment-Analyzer.git
Step 2: Install Dependencies
pip install -r requirements.txt
Step 3: Run Prediction
python prediction.py


✅ Results

The trained model successfully classifies tweets into:

Positive Sentiment

Negative Sentiment

🔮 Future Improvements

Add Neutral sentiment classification

Deploy using Flask/Streamlit

Real-time Twitter analysis

Web interface integration
