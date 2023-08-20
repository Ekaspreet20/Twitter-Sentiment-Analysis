# Twitter-Sentiment-Analysis

This GitHub repository contains code for performing sentiment analysis on Twitter data using various machine learning and deep learning techniques. The goal is to classify the sentiment of tweets as either positive or negative. The repository includes preprocessing, feature engineering, model training, and evaluation.

##### Distribution of data:
<img width="500" alt="image" src="https://github.com/Ekaspreet20/Twitter-Sentiment-Analysis/assets/65918628/0cf9e03c-9fad-4cd3-8e74-7575a3f19f99">

### Code Overview

The Jupyter Notebook `twitter_sentiment_analysis.ipynb` contains the following sections:

1. **Imports and Setup**: The necessary libraries and utilities are imported, including data preprocessing tools, machine learning models, and visualization packages.

2. **Data Loading and Preprocessing**: The Twitter dataset is loaded, and only the relevant columns ('sentiment' and 'text') are retained. 

3. **Text Preprocessing**: A preprocessing function is defined to clean and preprocess the text data. URLs, emojis, usernames, non-alphanumeric characters, and stopwords are removed. Words are lemmatized to their root forms. The processed text data is stored in a list.

4. **Word Clouds**: Word clouds are generated to visualize the most frequent words in both negative and positive tweets.
   Here is the positive Word Cloud:
  <img width="800" alt="image" src="https://github.com/Ekaspreet20/Twitter-Sentiment-Analysis/assets/65918628/9f09df34-a16f-447c-9c2a-ef2730891c85">


5. **Data Splitting and Transformation**: The dataset is split into training and testing sets. The training text data is transformed into TF-IDF features using the TfidfVectorizer.

7. **Model Training and Evaluation**:
   - Bernoulli Naive Bayes 
   - Linear Support Vector Classifier 
   - Logistic Regression 
   - A deep learning model (Artificial neural networks)
   - Ensemble Model: A hard voting ensemble is created using the trained models (Logistic Regression, LinearSVC, Bernoulli Naive Bayes).

**Conclusion**: A summary of the results and potential areas for improvement.
