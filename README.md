
# Social Media Sentiment Analysis

Analyze and visualize sentiment patterns in social media data to understand public opinion and attitudes towards specific topics or brands. This repository contains a Python script that performs sentiment analysis on social media data and provides visualizations of sentiment distribution, word clouds, and more.

## Introduction

This project is aimed at understanding public sentiment and opinions expressed on social media platforms, particularly in relation to specific topics or brands. The code in this repository performs the following tasks:

- Data preprocessing to clean and prepare social media data.
- Data visualization to provide insights into sentiment distribution and entity distribution.
- Text data processing and analysis, including the creation of word clouds and top word analysis for each sentiment category.
- Sentiment analysis using a machine learning model.
- Presentation of results, including optimized hyperparameters and accuracy scores.

## Getting Started

To run the code and perform sentiment analysis on your own data, follow these steps:

1. Clone this repository to your local machine.

2. Install the required Python libraries using the following command:

   ```shell
   pip install -r requirements.txt
   ```

3. Replace the sample data files (`twitter_training.csv` and `twitter_validation.csv`) with your own social media data.

4. Run the main script to execute sentiment analysis and visualization:

   ```shell
   python sentiment_analysis.py
   ```

5. View the generated visualizations and analyze the sentiment patterns.

## Data Preprocessing

Data preprocessing involves loading the data, handling missing values, and standardizing the sentiment labels.

## Data Visualization

Visualizations are created using Plotly and include pie charts for sentiment distribution, bar charts for entity distribution, and subplots with pie charts for sentiment distribution by the top entities.

## Text Data Processing and Analysis

Text data is processed to remove stopwords, perform lemmatization, and create word clouds. Top words for each sentiment category are also visualized.

## Sentiment Analysis Model

The code uses a machine learning model for sentiment analysis, specifically Logistic Regression with TF-IDF vectorization. Hyperparameters are optimized using GridSearchCV.

## Results

The results of sentiment analysis, including optimized hyperparameters and accuracy scores, are printed to the console.
