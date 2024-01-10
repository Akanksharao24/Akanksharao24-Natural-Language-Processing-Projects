# Sentiment Analysis on Israel-Palestine Conflict Comments

## Introduction

This project focuses on analyzing and gaining insights from comments related to the Israel-Palestine conflict, specifically gathered from Rediff. The scope of the project includes key components such as data preprocessing, sentiment analysis models, contextual analysis, and sentiment trends analysis.

## Code Overview

### Data Loading

The provided code successfully loads the Rediff comments data from the "pls_isl_conflict_comments.csv" file using the Pandas library. The data encoding is appropriately set to 'ISO-8859-1'.

### Data Limitation

The code wisely limits the data to the first 500 rows, ensuring the manageable size of the dataset for effective analysis.

### Data Preprocessing

#### VADER Sentiment Analysis

The code employs the VADER (Valence Aware Dictionary and sEntiment Reasoner) sentiment analysis model from NLTK. It calculates compound, positive, negative, and neutral sentiment scores for each comment.

## Sentiment Analysis Models

### Named Entity Recognition (NER)

The code performs Named Entity Recognition on the comments using NLTK's ne_chunk function. This aids in understanding the context and content by identifying named entities in the comments.

## Contextual Analysis

### Sentiment Trends Over Time

Unfortunately, the code does not explicitly analyze sentiment trends over time, as required by the project scope. To enhance this, grouping comments by date or other time-related data would be necessary to identify patterns and correlations with significant events.

## Code Execution and Results

The code loads and preprocesses the data, limiting it to the first 500 rows. It visualizes the count of comments by their respective sentiment scores, providing an initial overview of the dataset.

### Data Preprocessing and Visualization

The code tokenizes comments, performs part-of-speech tagging, and calculates sentiment scores. While sentiment scores are calculated, comments are not explicitly classified as "positive," "negative," or "neutral." This classification could be added as an enhancement.

### Sentiment Analysis

The code performs NER using ne_chunk, identifying named entities in the comments to aid in contextual analysis.

### Contextual Analysis

The code provides sentiment trend analysis with the following breakdown: Positive Comments: 32.40%, Negative Comments: 48.80%, Neutral Comments: 18.80%.

## Conclusion

In summary, the provided code covers essential aspects of the project scope, including data preprocessing, sentiment analysis using VADER, and basic contextual analysis through NER. However, there's room for improvement, particularly in analyzing sentiment trends over time. Developers are encouraged to enhance the code by incorporating time-related analysis to provide a more comprehensive understanding of sentiment changes during the Israel-Palestine conflict.
