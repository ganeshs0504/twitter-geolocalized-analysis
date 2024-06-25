# Geo-Localization and Newsworthiness Scoring

## Overview
This project involves analyzing a geo-tagged Twitter dataset, distributing the data over a grid in the city of London, and scoring the newsworthiness of tweets. The project includes three main parts:

1. Geo-localization: Distributing geo-tagged tweets in a grid and analyzing their distribution.
2. Newsworthiness Scoring: Developing a method to score tweets based on their quality.
3. Applying Newsworthiness Scoring: Applying the newsworthiness scoring method to the geo-tagged dataset.

## Table of Contents
- [Geo-Localization](#geo-localization)
- [Newsworthiness Scoring](#newsworthiness-scoring)
- [Applying Newsworthiness Scoring](#applying-newsworthiness-scoring)
- [Visualizations](#Visualizations)

## Geo-Localization
The first part of the project focuses on geo-localizing tweets. The main steps involved are:
- Converting a given geo-tagged Twitter dataset into a grid over the city of London.
- Populating the grid with the frequency of tweets in each cell.
- Analyzing the resulting grid data to retrieve insights such as the total number of tweets, geographical distribution, and average tweets per km².

### Key Features
- **Grid Creation**: Creating a grid based on specified coordinates using the Haversine distance method.
- **Tweet Mapping**: Mapping tweets to the grid cells based on their geo-coordinates.
- **Statistical Analysis**: Analyzing the grid data to gather insights on tweet distribution.

## Newsworthiness Scoring
The second part involves developing a method to score the newsworthiness of tweets. This includes:
- Tokenizing tweet text using the spaCy library.
- Calculating term frequencies for high-quality, low-quality, and background tweets.
- Computing newsworthiness scores based on term relevance.

### Key Features
- **Tokenization**: Efficient text processing using spaCy.
- **Term Frequency Calculation**: Determining the frequency of terms in different tweet categories.
- **Score Calculation**: Generating newsworthiness scores using statistical measures.

## Applying Newsworthiness Scoring
In the third part, the newsworthiness scoring method is applied to the geo-tagged dataset. This involves:
- Filtering tweets based on newsworthiness scores.
- Analyzing the distribution of scores across the dataset.
- Visualizing the data to identify trends and insights.

### Key Features
- **Threshold Analysis**: Testing various thresholds to classify tweets based on newsworthiness.
- **Empirical Analysis**: Conducting empirical analysis to validate the scoring method.
- **Visualization**: Creating visual representations of data distribution.

## Visualizations
**Grid layout for London city and heatmap for Twitter data**
![8b39c9c5-0136-48a5-bbb6-5bdd6fda2883](https://github.com/ganeshs0504/twitter-geolocalized-analysis/assets/145580150/26c72dd9-41ef-4c6b-b3cd-41e378e841d4)

**Data concentration**
![cbeadef4-5c2f-4c38-beba-7a4a66de04d0](https://github.com/ganeshs0504/twitter-geolocalized-analysis/assets/145580150/9f64330e-de67-4b40-9be3-aa12245e02cc)

**Newsworthiness Score Distribution**
![81f2c46d-6ef0-4280-9d52-89fa4528b59f](https://github.com/ganeshs0504/twitter-geolocalized-analysis/assets/145580150/d9837285-298b-4daf-937a-e7c1fc501eb3)
![db36aba6-40c0-44f9-939e-133853ad444e](https://github.com/ganeshs0504/twitter-geolocalized-analysis/assets/145580150/a57a5f6e-0f74-48ce-b7df-cca2769cb505)


