**README.md**

# Sentiment Analysis in Music Lyrics

## 1. Problem Definition

The problem addressed in this project is the analysis of sentiment in music lyrics to gain insights into the emotional content and themes expressed by different artists. Key aspects of the problem include:

- **Understanding Emotion in Music:**
  Music is a powerful medium for emotional expression, and artists often convey a range of sentiments through their lyrics.

- **Comparative Analysis:**
  Beyond individual analysis, the project seeks to compare the sentiment distributions among different artists, revealing patterns, trends, and unique characteristics.

- **User Interaction:**
  The inclusion of a user interface allows for an interactive exploration of sentiment analysis, enabling users to choose between analyzing a single artist's sentiments or comparing sentiments between two artists.

## 2. Existing Work

### Sentiment Analysis in Text

Numerous studies and projects have focused on sentiment analysis in textual data across various domains, such as social media, product reviews, and news articles.

### Music and Sentiment Analysis

Existing work in this domain involves the use of natural language processing (NLP) tools, sentiment lexicons, and machine learning models tailored to the unique language and context of song lyrics.

### Comparative Music Analysis

While comparative studies in music analysis often focus on genre classification and artist similarity, the specific exploration of sentiment across multiple artists is a less-explored area.

### User Interface for Sentiment Analysis

Incorporating a user-friendly interface for the specific domain of music lyrics sentiment analysis aligns with the goal of making the tool accessible and customizable for users with varying preferences and interests.

## 3. Data Sets Used

The code uses multiple datasets, each representing the song lyrics of a specific artist. The datasets are loaded using the Pandas library and are in CSV format.

Data Sets Used:
1. *Ariana Grande (df_a):*
- Dataset loaded from '/content/ArianaGrande.csv'.
  
2. *Beyonce (df_b):*
- Dataset loaded from '/content/Beyonce.csv'.
3. *Billie Eilish (df_c):*
- Dataset loaded from '/content/BillieEilish.csv'.
4. *Ed Sheeran (df_d):*
- Dataset loaded from '/content/EdSheeran.csv'.
5. *Justin Bieber (df_e):*
- Dataset loaded from '/content/JustinBieber.csv'.
6. *Katy Perry (df_f):*
- Dataset loaded from '/content/KatyPerry.csv'.
7. *Charlie Puth (df_g):*
- Dataset loaded from '/content/CharliePuth.csv'.
8. *Maroon 5 (df_h):*
- Dataset loaded from '/content/Maroon5.csv'.
9. *Post Malone (df_i):*
- Dataset loaded from '/content/PostMalone.csv'.
10. *Rihanna (df_j):*
- Dataset loaded from '/content/Rihanna.csv'.
11. *Selena Gomez (df_k):*
- Dataset loaded from '/content/SelenaGomez.csv'.
12. *Coldplay (df_l):*
- Dataset loaded from '/content/ColdPlay.csv'.
13. *Drake (df_m):*
- Dataset loaded from '/content/Drake.csv'.
14. *Dua Lipa (df_n):*
- Dataset loaded from '/content/DuaLipa.csv'.



**Preprocessing:**
- The 'Unnamed: 0' column is checked and renamed to 'S.no' if it exists. If not, a new 'S.no' column is added with sequential numbering.
- The sentiment scores and other relevant information are stored in DataFrames for further analysis.

## 4. Environment

The sentiment analysis scripts were developed and executed in a Python environment. The primary frameworks and libraries used for this project include:

1. **Python Version:** Python 3.10.12
2. **Pandas:** For data manipulation and analysis.
3. **NLTK (Natural Language Toolkit):** Specifically, the VADER sentiment analysis tool.
4. **Matplotlib:** For creating various charts and graphs.
5. **NumPy:** For numerical operations and array manipulations.
6. **TQDM:** To display progress bars.

## 5. Algorithmic Approach

### Step 1: Load and Preprocess the Data

- Import necessary Python libraries.
- Read CSV files containing lyrics data for multiple artists.
- Handle missing values and initialize the SentimentIntensityAnalyzer from NLTK.

### Step 2: Perform Sentiment Analysis for Individual Artists

- Iterate through lyrics for each artist and compute compound sentiment scores.
- Store sentiment scores in a Pandas DataFrame.
- Visualize sentiment distribution with a pie chart and compound scores with a bar graph.
- Display results, including the percentage of positive, negative, and neutral sentiments.

### Step 3: Compare Sentiment Analysis Across Artists

- For each pair of artists, repeat the sentiment analysis process.
- Store results for comparison and visualize using a bar chart.
- Display results, highlighting the percentage of each sentiment for each artist.

### Step 4: User Interaction

- Allow users to interactively choose analysis options.
- Prompt users to choose artists for analysis or comparison.

### Step 5: Visualization

- Utilize Matplotlib to create pie charts and bar graphs for visualizing sentiment distributions.

### Step 6: Results Compilation and Display

- Store sentiment analysis results in structured data frames.
- Display results, including percentages and visualizations, to the user.

## 6. Result

### Individual Sentiment Analysis

- Pie Chart: Distribution of positive, negative, and neutral sentiments.
- Bar Graph: Compound sentiment scores for each lyric.

### Comparison Sentiment Analysis

- Bar Chart: Comparison of positive, negative, and neutral sentiment percentages.

### Results Compilation

- Structured data frames with percentages of positive, negative, and neutral sentiments for each artist.

### User Interaction

- Interactive interface allowing users to choose analysis options and artists for exploration.

### Result Example (Comparison)

- ![image](https://github.com/Akanksharao24/Sentiment-Analysis-on-Music-NLP/assets/108931784/353f4a2d-5e0a-49c9-9ace-336e97401300)
- ![image](https://github.com/Akanksharao24/Sentiment-Analysis-on-Music-NLP/assets/108931784/0ec62945-16bd-4493-b1be-72ca0f182cfe)
- ![image](https://github.com/Akanksharao24/Sentiment-Analysis-on-Music-NLP/assets/108931784/928ca05d-8aba-479c-92d0-8c1dda34a00d)
- ![image](https://github.com/Akanksharao24/Sentiment-Analysis-on-Music-NLP/assets/108931784/ed706fb8-1c36-404c-95b0-93463500703b)
- ![image](https://github.com/Akanksharao24/Sentiment-Analysis-on-Music-NLP/assets/108931784/7e052d8c-b1e8-46a2-b0d3-181f379fdb43)






