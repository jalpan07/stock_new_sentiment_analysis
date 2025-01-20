# Stock News Sentiment Analysis

This project involves analyzing sentiment in stock news headlines using Natural Language Processing (NLP) techniques with Python. It focuses on headlines from the Finviz website for leading technology companies such as Apple (AAPL), Google (GOOG), Microsoft (MSFT), Amazon (AMZN), and Tesla (TSLA).

## Methodology

1. Data Collection

- Web Scraping: Utilized Beautiful Soup to scrape news headlines from Finviz.
- Data Handling: Stored headlines in a Pandas DataFrame and converted dates to datetime objects.
  
2. Sentiment Analysis

- Sentiment Score Calculation: Used the SentimentIntensityAnalyzer from NLTK to compute sentiment scores (-1 to 1).
- Normalization: Normalized scores for each day using mean and standard deviation.

3. Visualization

- Line Charts: Visualized sentiment trends over time for each company using Seaborn and Matplotlib.
- Heatmaps and Bar Charts: Provided additional insights into sentiment patterns.

4. WordCloud Generation

- WordClouds: Created visual representations of frequently occurring words in headlines using the WordCloud library.

## Libraries Used

- BeautifulSoup4
- NLTK
- Pandas
- NumPy
- Matplotlib
- Seaborn
- WordCloud
