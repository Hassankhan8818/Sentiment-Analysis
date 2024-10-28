# Sentiment Analysis on Product Reviews

This repository contains a Jupyter Notebook that performs sentiment analysis on a dataset of product reviews using natural language processing (NLP) techniques, combining the VADER sentiment analysis model and the RoBERTa transformer model from Hugging Face. This project provides a comprehensive approach to understanding and visualizing customer sentiment, making it suitable for applications like customer feedback analysis or social media sentiment monitoring.

You can download the data from the link given below:

https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews?resource=download
## Features

1.  **Data Loading and Exploration**:
    -   Loads a CSV file of product reviews and samples the first 500 entries.
    -   Visualizes the distribution of review scores to provide an overview of the data.
2.  **Text Preprocessing**:
    -   Tokenizes and applies part-of-speech tagging to individual review texts.
    -   Identifies named entities, adding structure to unstructured text data.
3.  **Sentiment Analysis Models**:
    -   **VADER (Valence Aware Dictionary and sEntiment Reasoner)**: A model optimized for social media and short-text sentiment analysis. Calculates polarity scores (positive, negative, neutral, and compound) for each review.
    -   **RoBERTa Transformer Model**: Incorporates the pre-trained RoBERTa model from Hugging Face for sentiment analysis, providing a robust, deep-learning-based approach.
    -   **Model Comparison**: Evaluates and compares sentiment predictions from VADER and RoBERTa, highlighting differences in performance and suitability for various types of text.
4.  **Data Visualization**:
    -   Plots sentiment distributions to illustrate the overall customer sentiment.
    -   Presents examples of both positive and negative reviews to demonstrate the effectiveness of both models.

## Requirements

-   Python libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `nltk`, `tqdm`, `transformers` (Hugging Face)
-   NLTK corpora and models: `punkt`, `averaged_perceptron_tagger`, `vader_lexicon`
-   Hugging Face Transformers library for RoBERTa

## How to Use

1.  **Clone the repository** and install the required libraries.
2.  **Run the notebook** to load the data, preprocess it, and calculate sentiment scores using both models.
3.  **Review the comparison** of VADER and RoBERTa sentiment scores to gain insights into the strengths and weaknesses of each model.

## Potential Applications

-   **Customer Feedback Analysis**: Use sentiment scores to evaluate product feedback and identify areas for improvement.
-   **Social Media Monitoring**: Apply the VADER and RoBERTa models to monitor and analyze sentiment on social media posts and comments.
-   **Model Evaluation**: Leverage the comparison between VADER and RoBERTa to choose a model that best fits specific sentiment analysis needs.
