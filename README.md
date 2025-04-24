# SentimentAnalysis
Python || RNN || LSTM
# Twitter Sentiment Analysis with RNN and LSTM

Welcome to the **Twitter Sentiment Analysis** project! This Jupyter Notebook (`Tutorial9LSTM&RNN.ipynb`) uses Recurrent Neural Networks (RNN) and Long Short-Term Memory (LSTM) models to predict whether tweets about Trump are positive or negative.It’s like teaching a robot to read tweets and decide if they’re happy 😊 or critical 😣 by analyzing their words. This README will guide you through the project, from setup to running the code, so anyone can understand and use it. are you ready! Let’s dive in!

## 📖 Project Overview

This project analyzes a dataset of Trump-related tweets (`trum_tweet_sentiment_analysis.csv`) to classify their sentiment as:
- **Positive (1)**: Tweets with favorable opinions.
- **Negative (0)**: Tweets with critical or unfavorable opinions.

We use two deep learning models:
- **Simple RNN**: A basic recurrent network that processes text sequences but struggles with long-term dependencies.
- **LSTM**: An advanced RNN that remembers important information over longer sequences, ideal for tweets.

**Analogy**: Imagine the RNN as a short-memory reader skimming tweets, while the LSTM is a careful reader remembering key details to understand the sentiment better. The notebook preprocesses tweets, trains both models, compares their performance, and even includes a GUI to predict sentiment for new tweets. **What is going on** Keep reading to find out!

### Key Features
- **Dataset**: `trum_tweet_sentiment_analysis.csv` (tweets with text and sentiment labels).
- **Preprocessing**: Cleans tweets by removing URLs, emojis, stopwords, and lemmatizing words.
- **Models**: Simple RNN and LSTM for binary sentiment classification.
- **Visualization**: Word clouds, loss/accuracy plots, and a Tkinter GUI for interactive predictions.
- **Tools**: TensorFlow/Keras, NLTK, Pandas, Matplotlib, WordCloud, Tkinter, Contractions.

## 🛠️ Setup Instructions

To run this notebook, you’ll need a Python environment with the required libraries. Follow these steps to set up:

### Prerequisites
- **Python**: Version 3.6+ (tested with 3.9.13 in the notebook).
- **Jupyter Notebook**: To run `.ipynb` files.
- **Dataset**: Download `trum_tweet_sentiment_analysis.csv` and place it in the same directory as the notebook.

### Installation
1. **Clone the Repository**:
   ```bash
   git clone <https://github.com/Abinash7G/SentimentAnalysis.git>
   cd <your-repo-folder>
