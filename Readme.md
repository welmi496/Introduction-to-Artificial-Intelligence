# Sentiment Analysis with Traditional Models and BERT

## Project Overview
This project performs sentiment analysis on the IMDb public movie review dataset. The objective is to classify movie reviews as positive or negative using:
- Bag of Words
- TF-IDF
- Word2Vec embeddings
- Logistic Regression
- Linear Support Vector Machine
- BERT (`bert-base-uncased` fine-tuning)

## Dataset
The dataset used is the IMDb dataset from the Hugging Face `datasets` library.

## Project Tasks Completed
- Data loading and preprocessing
- Text cleaning and transformation
- Feature engineering with Bag of Words, TF-IDF, and Word2Vec
- Traditional model training and tuning using GridSearchCV
- BERT fine-tuning for sentiment classification
- Evaluation using accuracy, precision, recall, F1-score, ROC-AUC
- Confusion matrices, ROC curves, and embedding visualization
- Report summary for PDF submission

## Output
The notebook produces:
- cleaned text data
- vectorized features
- trained traditional models
- fine-tuned BERT model
- evaluation metrics
- visualizations
- report text for final submission
