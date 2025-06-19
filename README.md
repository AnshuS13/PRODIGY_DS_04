# Twitter Sentiment Analysis on Social Media Data

## Project Overview

This project analyzes public sentiment toward various brands and topics using a large Twitter dataset.  
The dataset contains tweets labeled as Positive, Negative, Neutral, or Irrelevant about different entities such as Microsoft, Facebook, and popular video games.

## Project Description

This project analyzes sentiment patterns in a large Twitter dataset related to various brands and topics. Using natural language processing techniques, the tweets are cleaned and preprocessed to remove noise such as URLs, mentions, and special characters. The cleaned data is then explored to understand the distribution of sentiments labeled as Positive, Negative, Neutral, or Irrelevant.

Visualizations such as bar charts and pie charts provide an overview of overall sentiment trends. Word clouds for each sentiment category highlight the most frequently used words, giving insight into the language and themes expressed by users. Additionally, an optional entity-level sentiment analysis groups tweets by brands or topics, helping identify which entities receive more positive or negative attention.

The insights gained from this analysis can help marketers and brand managers understand public opinion and tailor strategies accordingly.

---

## Dataset

- Source: [Twitter Entity Sentiment Analysis Dataset (Kaggle)](https://www.kaggle.com/datasets/jp797498e/twitter-entity-sentiment-analysis)  
- Size: ~74,682 tweets  
- Columns: `id`, `entity` (brand/topic), `sentiment` (Positive, Negative, Neutral, Irrelevant), `text` (tweet content)

---

## Key Features

- Data loading and cleaning (removing URLs, mentions, hashtags, special characters)  
- Exploratory data analysis of sentiment distribution  
- Visualization of common words by sentiment category using word clouds  
- Optional entity-level sentiment analysis to understand brand-specific sentiment trends

---

## Technologies Used

- Python 3.x  
- Pandas  
- Matplotlib  
- Seaborn  
- WordCloud  
- Regex (for text cleaning)

---

## Author

Anshu Singh
www.linkedin.com/in/anshusingh1213
