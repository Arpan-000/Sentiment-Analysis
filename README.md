# Sentiment-Analysis 


---

# Movie Reviews Sentiment Analysis

This project performs sentiment analysis on movie reviews using Natural Language Processing (NLP) techniques. It employs the NLTK library for text processing, a Naive Bayes classifier for sentiment classification, and utilizes word clouds for visualization.

## Project Structure

- **Data Preparation:**
  - The movie reviews are sourced from the NLTK movie_reviews corpus.
  - Positive and negative reviews are processed, and word clouds are generated to visually represent common words in each sentiment.

- **Exploratory Data Analysis (EDA):**
  - A bar chart displays the distribution of positive and negative reviews.

- **Sentiment Analysis:**
  - The dataset is split into a training set and a test set using the `train_test_split` function from scikit-learn.
  - Features are extracted from the reviews, removing stop words.
  - A Naive Bayes classifier is trained on the training set and evaluated on the test set.

## Project Files

- **main.py:** Contains the main code for data preparation, EDA, and sentiment analysis.

## Dependencies

- nltk
- scikit-learn
- wordcloud
- matplotlib

## Setup

1. Install the required dependencies using `pip install -r requirements.txt`.
2. Run the `main.py` script to execute the sentiment analysis.

## Results

- The accuracy of the sentiment classifier on the test set is displayed in the console.

## Note

Ensure that you have NLTK, scikit-learn, wordcloud, and matplotlib installed before running the code.

Feel free to explore and modify the code to suit your needs.

---
