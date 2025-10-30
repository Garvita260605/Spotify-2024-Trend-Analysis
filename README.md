 Spotify-2024-Trend-Analysis
Analyzed the most streamed Spotify songs of 2024 using Python to uncover music trends and listener behavior. Applied EDA, Z-tests, and NLP to study the impact of explicit content and artist popularity across platforms. Used Pandas, Seaborn, and Matplotlib for data cleaning, visualization, and insight generation on streaming patterns.

Overview: This project focuses on performing Descriptive Analytics on the Most Streamed Spotify Songs of 2024 using Python.
It aims to uncover music trends, analyze listener behavior, and understand what makes a song popular across various platforms such as Spotify, YouTube, TikTok, and Apple Music.

Using Exploratory Data Analysis (EDA), Hypothesis Testing, and Natural Language Processing (NLP), the project identifies key insights about streaming patterns, artist dominance, and the influence of explicit content on popularity.

Objectives:
Analyze the top streamed tracks of 2024 to identify trends in streaming behavior.
Compare the performance of explicit vs. non-explicit tracks using statistical testing.
Use NLP techniques to classify lyrics as explicit or non-explicit.
Visualize key insights to understand factors contributing to song success.

Motivation:
Streaming platforms have revolutionized how audiences consume music. This project explores how data analytics and Python can reveal trends behind hit songs, audience preferences, and cross-platform engagement patterns — offering valuable insights for artists, record labels, and data enthusiasts.

Dataset
Source: Kaggle - Most Streamed Spotify Songs 2024

Key Columns Include:

Track, Album Name, Artist, Release Date
Spotify Streams, YouTube Views, TikTok Likes, Apple Music Playlist Count
Track Score, Popularity, Explicit Track, and other engagement metrics

Tools & Libraries Used
Python 3.x
Pandas – Data manipulation and cleaning
NumPy – Numerical computations
Matplotlib & Seaborn – Data visualization
NLTK / VADER – NLP-based text sentiment and explicitness analysis
SciPy / Statsmodels – Z-test and statistical analysis

 
 Methodology
1. Data Cleaning
Removed null values, duplicates, and irrelevant columns.
Converted date formats and standardized categorical data.

2. Exploratory Data Analysis (EDA)
Visualized distributions of streams, likes, and popularity across platforms.
Identified top-performing artists and tracks.

3. Hypothesis Testing (Z-Test)
Compared mean Spotify streams between explicit and non-explicit tracks.
Found a significant difference (p-value < 0.05), indicating explicit content
