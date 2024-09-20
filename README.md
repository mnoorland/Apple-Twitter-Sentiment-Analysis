# Sentiment Analysis of Apple Inc. on Twitter

## Project Overview
This project focuses on performing sentiment analysis on 2,000 tweets related to **Apple Inc.**, collected via the Twitter API. The goal was to understand public sentiment towards Apple's brand and products by classifying tweets into **positive**, **neutral**, and **negative** categories. Using **Natural Language Processing (NLP)** techniques, we pre-processed the data, tokenized the text, and trained a **Random Forest Classifier** to categorize the sentiments. The model achieved an accuracy of 89%, providing insights into how customers perceive Apple.

## Objectives
- **Classify tweets** related to Apple as positive, neutral, or negative using a sentiment analysis model.
- **Analyze customer sentiment trends** to highlight areas where Apple could improve brand perception.
- **Visualize the results** using pie charts, bar graphs, and word clouds to showcase key findings.

## Key Features
- **Text Preprocessing**: Handled missing data, tokenized text, and padded sequences to prepare the dataset for model training.
- **Sentiment Classification**: Trained a Random Forest model to classify the tweets into positive, neutral, or negative sentiments.
- **Visualization**: Created sentiment distribution pie charts, bar graphs, and word clouds to visualize key findings.

## Tools & Technologies
- **Python (Jupyter Notebook)**: Used for data preprocessing, model training, and visualization.
- **NLTK**: For natural language processing, including tokenization and sentiment analysis.
- **scikit-learn**: To train the Random Forest Classifier.
  
## Files Included
- **[Jupyter Notebook](./apple-sentiment-analysis.ipynb)**: Contains the code for data preprocessing, model training, and evaluation.
- **[Presentation](./web_social.pdf)**: Slide deck showcasing the visualizations and analysis presented to the faculty.

## Dataset
The dataset consists of 2,000 tweets about Apple Inc., with the following features:
- **Text**: The content of each tweet.
- **Sentiment Labels**: Positive (1), Neutral (0), and Negative (-1), used as target labels for classification.

## Visualization Summary
- **Pie Chart**: Showed the distribution of sentiments, indicating a 49.1% positive, 42.1% neutral, and 8.8% negative sentiment.
- **Bar Graph**: Illustrated the count of tweets for each sentiment, with neutral and negative sentiments dominating the dataset.
- **Word Cloud**: Highlighted frequently mentioned words in positive and negative tweets, such as "Apple" and "APPL."
