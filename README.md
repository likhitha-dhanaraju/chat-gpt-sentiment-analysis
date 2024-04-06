# Public Sentiment Analysis of Large Language Models: Before and After ChatGPT Launch

## Description

This repository contains the research report and codebase for a sentiment analysis project focusing on public perceptions of large language models (LLMs) before and after the launch of ChatGPT. The study aims to understand shifts in sentiment, prevalent topics of discussion, and overall public reception of AI technologies such as ChatGPT.

## Table of Contents

- [Description of Research Question](#description-of-research-question)
- [Methodology](#methodology)
  - [Data Sources](#data-sources)
  - [Data Collection](#data-collection)
  - [Data Cleaning and Preprocessing](#data-cleaning-and-preprocessing)
- [Analysis Performed](#analysis-performed)
  - [WordCloud](#wordcloud)
  - [Corpus Matrix](#corpus-matrix)
  - [Sentiment Analysis](#sentiment-analysis)
  - [Topic Modeling](#topic-modeling)
- [Conclusions/Interpretations](#conclusionsinterpretations)
- [Limitations](#limitations)
- [Individual Contributions](#individual-contributions)

## Description of Research Question

The research question investigates the public sentiment regarding large language models, specifically focusing on the period before and after the launch of ChatGPT. It aims to identify shifts in attitudes, prevalent sentiments, and key topics of discussion to understand the impact of ChatGPT on public perception of AI technologies.

## Methodology

### Data Sources

The study employed a multi-source data collection approach, primarily focusing on Twitter and Reddit to capture a diverse range of public sentiments. These platforms were chosen for their accessibility and richness of data.

### Data Collection

Twitter data was collected using hashtags and keywords related to ChatGPT and AI technology. Reddit data was obtained from targeted subreddits discussing AI-related topics.

### Data Cleaning and Preprocessing

Text data underwent preprocessing steps such as part-of-speech tagging, lowercasing, punctuation removal, tokenization, stopword removal, lemmatization, and noise reduction to prepare it for analysis.

## Analysis Performed

### WordCloud

Word clouds were generated to visualize key themes from both pre- and post-ChatGPT release datasets, providing insights into prevalent topics of discussion.

### Corpus Matrix

A corpus matrix was developed using the gensim library, involving tokenization, dictionary creation, corpus representation, TF-IDF modeling, and transformation to analyze the distribution of terms across documents.

### Sentiment Analysis

Sentiment analysis was conducted using the NLTK SentimentIntensityAnalyzer to identify positive and negative sentiments in the datasets and calculate overall sentiment scores.

### Topic Modeling

Topic modeling was performed using Latent Dirichlet Allocation (LDA) to identify latent topics within the datasets, providing deeper insights into the main discussion themes.

## Conclusions/Interpretations

The analysis revealed shifts in public sentiment, with ChatGPT's launch leading to more focused discussions on its capabilities, applications, and integration with other technologies. While sentiment became slightly more positive post-ChatGPT, the change was not revolutionary, indicating an evolutionary progression in public perception.

## Limitations

- Data collection bias due to reliance on Twitter and Reddit.
- Language limitations in translating non-English content.
- Potential inaccuracies in sentiment analysis algorithms.
- Temporal constraints in capturing long-term sentiment shifts.
- Evolving nature of public discourse impacting conclusions.
