# Analyzing VAR Sentiments in the English Premier League Using Web Scraping and Machine Learning
   This report aims to breakdown the profound impact of Video Assistant Referee (VAR) implementation on referees, teams, and the Premier League Football Association (FA).

## Overview
  This project explores the impact of Video Assistant Referee (VAR) decisions in the English Premier League (EPL) from 2019 to 2023. Using data scraped from various websites, it employs Natural Language Processing (NLP) and Machine Learning (ML) techniques to analyze VAR incident descriptions and classify sentiments as FOR, AGAINST, or NEUTRAL. The study provides valuable insights for referees, team managers, and the Football Association (FA) to enhance VAR's application and improve decision-making in football officiating.

## Data Description
  The dataset includes:
    - Match Details: Teams, scores, and VAR descriptions.
    - Referee Statistics: Yellow/red cards and games officiated.
    - Sentiments: VAR incident outcomes classified as FOR, AGAINST, or NEUTRAL (later reclassified for accuracy).

## Key Highlights
  - Web Scraping: Data was extracted from FBREF, SoccerBase, and ESPN using Python libraries such as BeautifulSoup and Selenium WebDriver.
  - NLP Techniques: Text preprocessing (tokenization, lemmatization, and stop-word removal). Feature extraction using Term Frequency-Inverse Document Frequency (TF-IDF).
  - Machine Learning Models: Logistic Regression, Random Forest, Support Vector Machines, Gradient Boosting and Ensemble Model.
  - Model Evaluation: Classification metrics: Accuracy, Precision, Recall, and F1-Score. Gradient Boost Classifier emerged as the top performer


## Repository Contents
  - Report: Detailed report consisting of the  methods, analysis, limitations and findings.
  - Code: Python scripts used for web scraping, NLP, and ML model implementation.

## Acknowledgments
  - Data Sources: FBREF, SoccerBase, ESPN.
  - Inspiration: Research on VAR applications in football and sentiment analysis techniques.
