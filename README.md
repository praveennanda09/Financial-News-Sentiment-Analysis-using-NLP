# Financial News Sentiment Analysis Project

## Introduction
In the financial sector, news articles significantly impact stock prices and investor decisions. The challenge lies in the overwhelming volume of news, making it impossible for investors to manually assess whether the sentiment of a report is positive, negative, or neutral in real-time. Misinterpretation of sentiment can lead to poor financial decisions.

This project aims to apply Natural Language Processing (NLP) techniques to automatically classify financial news into positive, negative, or neutral sentiment, enabling faster, data-driven decision-making for investors and businesses.

## Dataset Overview
- **Entries**: 4,845
- **Columns**: 2
  - **Sentiment** (e.g., "neutral", "negative", "positive"): Represents the sentiment label of the financial news. It classifies the sentiment of the corresponding text in each row.
  - **Text**: Contains financial news or statements, used for analyzing and classifying the sentiment based on content.
- **Data Quality**: No missing values, indicating both columns are fully populated.

The dataset is structured for sentiment analysis, with the goal of classifying financial news into positive, negative, or neutral sentiment. By applying NLP techniques, we aim to build models that can automatically predict the sentiment of new financial articles.

## Conclusion
- Utilized **LSTM** combined with word embeddings such as **Word2Vec** and **GloVe** for accurate sentiment classification.
- Achieved high accuracy in classifying sentiments as positive, negative, or neutral.
- Conducted careful **hyperparameter tuning** and thorough **data preprocessing** to optimize model performance.
- The insights gained can help stakeholders make informed decisions based on market sentiment.
- Potential for real-time sentiment analysis and future improvements to enhance decision-making processes.
