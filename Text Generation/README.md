# Corpus Analysis Toolkit

## Overview

The Corpus Analysis Toolkit is a versatile tool designed to analyze textual corpora using various techniques. This README provides an overview of the features, functionalities, and evaluations included in the toolkit.

## Corpus Chosen

The toolkit begins by reading a corpus from a text file named "Mythology.txt."

## Preprocessing the Corpus

The corpus undergoes the following preprocessing steps:
- Removal of non-alphanumeric characters.
- Conversion of text to lowercase.
- Tokenization, splitting the text into words.

## Heap's Law Model

- Applies Heap's Law to estimate the relationship between vocabulary size (V) and the number of tokens (N) in a text.
- Estimates parameters K and beta through curve fitting and prints the results.
- Visualizes Heap's Law with a plot showcasing the data and the fitted curve.

## Term Frequency Analysis

- Calculates the frequency distribution of words.
- Sorts the top 50 terms by frequency and plots them in a bar chart.

## Bigram Collocations

- Extracts bigram collocations from the corpus using the Pointwise Mutual Information (PMI) scoring method.
- Sorts the top 50 collocations by frequency and plots them in a bar chart.

## N-Gram Analysis

- Allows user input for a keyword and the desired n-gram size (e.g., bigrams, trigrams).
- Performs tokenization and generates n-grams of the specified size.
- Filters n-grams containing the keyword and displays the text centered around the keyword in the selected n-gram.

## N-Gram Sparsity Analysis

- Calculates the sparsity of n-grams by comparing the number of unique n-grams to the total possible n-grams.
- Prints results and comments on whether the sparsity is low or high.

## Language Model and Perplexity Calculation

- Utilizes a simple language model to calculate perplexity for a test dataset.
- Takes the test dataset as a list of sequences.
- Computes log-likelihood and total word count for the test dataset.
- Calculates perplexity based on log-likelihood and total words.

## Evaluation

### Intrinsic Evaluation

- **Heap's Law Analysis:** Assesses vocabulary growth with increasing text size.
- **Term Frequency Analysis:** Provides insights into the most frequent terms in the corpus.
- **Bigram Collocation Analysis:** Identifies meaningful word pairs that co-occur.

### Extrinsic Evaluation

- No specific extrinsic evaluation is provided in the code, but the language model perplexity calculation serves as a measure of the model's performance on a given test dataset.

## Summary/Conclusions

- The code effectively preprocesses the chosen corpus and conducts various analyses, offering valuable insights into vocabulary growth, term frequency, and meaningful word pairs.
- Heap's Law analysis demonstrates the richness of the text as the corpus size increases.
- Term frequency analysis identifies crucial terms in the corpus, potentially indicating significant keywords or topics.
- Bigram collocations reveal meaningful word pairs, aiding in understanding relationships within the text.
- N-gram analysis allows users to extract and explore text around specific keywords, beneficial for summarization or topic extraction.
- Sparsity analysis indicates coverage of observed n-grams compared to the total possible n-grams.
- Perplexity calculation assesses the language model's performance in predicting text sequences.
