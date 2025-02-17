# NLP and Machine Learning for Forward Guidance & Market Sentiment Analysis

## Overview

This repository contains the code and analysis for applying Natural Language Processing (NLP) and machine learning techniques to analyze forward guidance and market sentiment. The project focuses on examining speeches by the Chair of the U.S. Federal Reserve and minutes from the Federal Open Market Committee (FOMC) from 2001 to 2019 to assess their impact on financial markets. The authors of the assignment are Paula Luvini, Florencia Ludueña, and Facundo Marconi.

## Methodology

1. **Web Scraping**: Extracting the corpus of speeches and FOMC minutes using `BeautifulSoup` and `requests`.
2. **Text Preprocessing**: Cleaning text, removing stopwords, lemmatization, and vectorization using `TF-IDF`.
3. **Market Sentiment Analysis**: Measuring sentiment and tone in the speeches.
4. **Feature Engineering**: Extracting linguistic and financial indicators.
5. **Classification Model**: Training an SVM classifier with grid search and cross-validation to predict market volatility changes based on speech content.

## Results

- The analysis explores how different tones in Federal Reserve speeches correlate with financial market volatility.
- The classifier helps predict market reactions based on speech sentiment and content.
- Findings contribute to understanding the effectiveness of forward guidance as a monetary policy tool.
