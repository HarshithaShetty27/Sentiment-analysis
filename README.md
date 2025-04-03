# Sentiment Analysis Using LSTM  

## Project Overview  
This project is a **Sentiment Analysis model** that classifies text reviews as **positive (1) or negative (0)** using **Deep Learning (LSTM - Long Short-Term Memory Networks)**. The model is trained on a dataset of reviews, where each review is converted into a numerical format using **tokenization and word embeddings**.  

## Features  
✅ Preprocesses text data using **Tokenization & Padding**  
✅ Uses an **LSTM-based Neural Network** for text classification  
✅ Implements **word embeddings (Embedding Layer)** for meaningful word representations  
✅ **Trained using Adam optimizer** and **Binary Cross-Entropy Loss**  
✅ Achieves high accuracy in predicting sentiment  

## Tech Stack  
- **Python**  
- **TensorFlow / Keras**  
- **Pandas** (for data processing)  

## Model Architecture  
The LSTM model consists of:  
1️⃣ **Embedding Layer** - Converts words into dense vector representations  
2️⃣ **LSTM Layer** - Captures sequential dependencies in text  
3️⃣ **Dense Layer (Sigmoid Activation)** - Outputs a probability between 0 and 1  

## How It Works  
1️⃣ **Load Dataset** (Text Reviews + Sentiment Labels)  
2️⃣ **Preprocess Text** (Tokenization, Padding)  
3️⃣ **Train the Model** (LSTM with Word Embeddings)  
4️⃣ **Evaluate Performance** (Accuracy, Loss Metrics)  
5️⃣ **Make Predictions** (New Review Sentiment Detection)  

## Installation  
To set up the project, follow these steps:  

### Clone the repository  
```bash
git clone https://github.com/yourusername/sentiment-analysis.git
cd sentiment-analysis
