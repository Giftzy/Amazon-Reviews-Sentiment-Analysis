# Amazon-Reviews-Sentiment-Analysis

📌 Overview

This project analyzes Amazon product reviews using TextBlob for sentiment analysis. It processes raw review text, assigns sentiment polarity scores, and classifies reviews into positive, negative, or neutral categories. The notebook also evaluates prediction accuracy on a train-test split dataset.

🛠️ Features
Load and preprocess Amazon reviews dataset (amazon_reviews.csv).
Perform sentiment polarity scoring with TextBlob.
Categorize reviews into Positive, Negative, and Neutral classes.
Split data into training and test sets for evaluation.
Measure model accuracy using Scikit-learn.
Display sample predictions with polarity scores.

📂 Project Structure
- NLP_amazon_reviews.ipynb     # Main notebook with code & analysis
- amazon_reviews.csv  # Dataset used (Amazon reviews)

⚙️ Requirements
Ensure the following Python packages are installed:

pip install pandas textblob scikit-learn

🚀 Usage
- Clone or download this repository.
- Place the dataset in the folder: ./excel_work-data/amazon_reviews.csv
- Open the Jupyter Notebook:
- jupyter notebook: NLP_amazon_reviews.ipynb
- Run all cells to reproduce the sentiment analysis pipeline.

📊 Methodology
1.  Data Loading & Cleaning
      -  Read reviews from CSV.
      -  Ensure reviewText is string type and handle missing values.
2.  Sentiment Analysis
      -  Compute polarity scores using TextBlob.
      -  Assign labels:
            - positive (polarity > 0)
            - negative (polarity < 0)
            - neutral (polarity = 0)
3.  Model Evaluation
      -  Train-test split (80-20).
      -  Predict sentiment on test set.
      -  Compute accuracy with accuracy_score.
4.  Result Visualization
      -  Display sample reviews with polarity and predicted label.

📈 Results
    - The notebook prints out:
        - Dataset statistics
        - Sample predictions with polarity values
        - Accuracy score of the sentiment classifier
