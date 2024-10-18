# IMDB Sentiment Analysis using NLP

This project performs sentiment analysis on IMDB movie reviews using Natural Language Processing (NLP) techniques. It classifies reviews as **positive** or **negative** based on the content of the text.

## Features

- **Data Preprocessing**: 
  - The text data is cleaned by removing stopwords, lowercasing, and tokenizing.
  - Lemmatization and other normalization techniques are applied to standardize the text.

- **Modeling**: 
  - Sentiment classification is done using pre-trained NLP models like **BERT** for word embeddings.
  - Tokenized text is converted to embeddings using **Hugging Face's Transformers** library.

- **Training and Fine-Tuning**:
  - The BERT model is fine-tuned on the IMDB dataset to optimize sentiment classification.
  
- **Evaluation**:
  - The model's performance is evaluated using metrics such as accuracy, precision, recall, and F1-score.
  
- **Real-Time Prediction**:
  - The model can classify sentiment for new user-provided reviews.

## Technologies Used

- **Python**
- **Hugging Face Transformers** for model training and fine-tuning
- **Pandas** and **NumPy** for data manipulation
- **Matplotlib** for visualization
- **Scikit-learn** for evaluation metrics

## How to Use

1. Clone the repository.
2. Install dependencies: `pip install -r requirements.txt`
3. Run the notebook or script to load the model and classify IMDB reviews.
