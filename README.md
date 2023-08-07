# Sentiment Analysis on IMDB Movie Reviews
## Introduction
This project aims to perform sentiment analysis on movie reviews from the IMDB database. The project utilizes Python along with various libraries like Pandas, TextBlob, WordCloud, and Matplotlib to efficiently process, analyze, and visualize the data.

## Data Source
The movie reviews data is sourced from Kaggle, a renowned platform for data science and machine learning projects. The data is organized and stored in SQLite format, providing a lightweight and convenient database system for working with the data.

## Data Analysis and Sentiment Analysis
The project begins with data analysis, where Python's Pandas library is employed to retrieve and manipulate the data from the SQLite database. Data preprocessing tasks, including lowercasing, punctuation removal, and tokenization, are carried out to ensure the text data is suitable for sentiment analysis.

For sentiment analysis, the TextBlob library is utilized. This powerful natural language processing tool allows us to analyze the sentiments of each movie review, classifying them as positive, negative, or neutral.

## Visualization of Results
To present the sentiment analysis results in a visually appealing and informative manner, Python's Matplotlib library is utilized. Various visualizations, such as bar charts and word clouds, are created to showcase the distribution of sentiments across the movie reviews.

Word clouds are generated using the WordCloud library, highlighting the most frequently occurring words in positive and negative movie reviews. These word clouds aid in identifying the most significant keywords associated with positive and negative sentiments.

## Key Takeaways and Significance
This project provides valuable insights into the sentiments expressed by viewers in the IMDB movie reviews. The sentiment analysis, complemented by data visualizations, allows for a deeper understanding of the audience's perception of the movies.

## How to Run the Project
1. Clone the repository to your local machine.
2. Install the required dependencies listed in the requirements.txt file.
3. Run the Python script sentiment_analysis.py to perform sentiment analysis on the IMDB movie reviews.
4. The script will generate visualizations and save them in the output directory.

## Acknowledgments
The project was made possible with the support of the IMDB dataset from Kaggle and the invaluable contributions of the open-source Python libraries Pandas, TextBlob, WordCloud, and Matplotlib.
