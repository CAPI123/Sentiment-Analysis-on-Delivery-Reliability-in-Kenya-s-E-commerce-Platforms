# Sentiment Analysis on Delivery Reliability in Kenya’s E-commerce Platforms

This project analyzes delivery reliability and customer sentiment for major e-commerce platforms in Kenya: **Jumia**, **Kilimall**, and **Glovo**. It uses user reviews from the Google Play Store to extract insights about delivery experiences, common complaints, and suggestions for improvement.

## Features

- **Data Collection**: Fetches recent reviews from the Google Play Store using `google-play-scraper`.
- **Filtering**: Isolates delivery-related reviews using relevant keywords.
- **Sentiment Analysis**: Classifies reviews as Positive, Neutral, or Negative using TextBlob.
- **Visualization**: Provides pie charts and bar plots to show sentiment distribution and review counts per platform.
- **Text Analysis**: Extracts common words, bigrams, and suggestion-oriented phrases from reviews.
- **Actionable Insights**: Highlights key areas for improvement for each platform.

## Project Structure

- `Sentiment Untitled-1.ipynb`: Main Jupyter notebook containing all code for data collection, processing, analysis, and visualization.
- `delivery_related_reviews.csv`: Exported CSV of filtered delivery-related reviews.

## Requirements

- Python 3.7+
- Jupyter Notebook
- Packages:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - textblob
  - nltk
  - scikit-learn
  - wordcloud
  - google-play-scraper

Install dependencies with:
```sh
pip install pandas numpy matplotlib seaborn textblob nltk scikit-learn wordcloud google-play-scraper
```

## Usage

1. **Open** `Sentiment Untitled-1.ipynb` in Jupyter Notebook or VS Code.
2. **Run all cells** sequentially to:
   - Fetch and filter reviews
   - Perform sentiment analysis
   - Visualize results
   - Extract and display common suggestions and complaints
3. **Review the outputs** for insights and recommendations.

## Key Insights

- Customer service and delivery time are the most common areas of concern.
- Each platform has unique feedback trends (e.g., Jumia: delivery fees, Kilimall: customer service, Glovo: app/order management).
- Visualizations help compare sentiment and complaint frequency across platforms.

## License

This project is for educational and research purposes.

