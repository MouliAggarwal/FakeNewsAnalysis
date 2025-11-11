# FakeNewsAnalysis

## Project Description
This project aims to analyze patterns, linguistic features, and sentiment differences between fake and real news articles using a dataset sourced from Kaggle. The goal is to understand the distinguishing characteristics of fake versus real news to support future efforts in misinformation awareness and automated detection.

## Dataset Information
### Source: Kaggle


### Content: The dataset consists of news articles labeled as 'fake' or 'real.' It includes fields such as title, author, content, and publication date.


### Key Features:

- Title- The headline or main title of the news article.

- Text- Full body text content of the news article.

- Date- Publication date of the article, useful for trend analysis over time.

- Source- The original publisher or platform where the news was released.

- Label- Indicator specifying whether the article is verified as real or identified as fake.

- Tone- Sentiment or emotional tone analysis of the article’s language, categorized typically as positive or negative.

This structured dataset enables detailed analysis for identifying patterns, trends, and distinctions between genuine and misleading news content. It supports various methods like natural language processing, sentiment analysis, and machine learning for fake news detection and insight extraction.

## Tone Used

### Microsoft Excel: Used for initial data compilation, cleaning (removal of duplicates, missing values), and for creating preliminary visualizations such as charts and graphs.

### Google Colab: Served as the primary platform for Python analysis, data manipulation, and visualization.

### Python Libraries:
pandas: Used for efficient data manipulation and analysis.
NLTK/TextBlob: Employed for Natural Language Processing, sentiment, and tone analysis on the news articles.

## Analysis Workflow
1. Data Preparation
 Imported the dataset into Microsoft Excel for initial inspection.
 Cleaned the data by removing duplicates and handling missing values to ensure accuracy for further analysis.

2. Exploratory Data Analysis (EDA)
Generated summary statistics (e.g., counts by label, basic descriptive stats) in Excel.
Created visual summaries, such as bar and pie charts, to explore trends in the dataset.

3. Data Import Into Python
 Loaded the cleaned dataset into Google Colab for in-depth analysis using Python.

4. Sentiment and Tone Analysis
 Applied Natural Language Processing (NLP) techniques via NLTK/TextBlob to assess the polarity and subjectivity of news articles.
Compared linguistic patterns between fake and real news articles.

5. Visualization and Interpretation
 Leveraged Python libraries to produce visualizations illustrating patterns, distributions, and key differentiators between authentic and fake news.

## Result Summary
