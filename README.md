# Product Review Analyzer ⭐

Analyzes product reviews to extract sentiment,
keywords and insights — like Amazon and Flipkart do internally.

## Live Demo
[Click here](https://appuct-review-analyzer-3sssteq3twdgcq5xm2hwee.streamlit.app)

## Features
- 3 sample products with real-looking reviews
- Rating distribution visualization
- Sentiment distribution pie chart
- Per-review sentiment trend chart
- Positive vs negative keyword extraction
- Word cloud generation
- Rating vs sentiment correlation scatter
- Upload your own CSV reviews
- Paste custom reviews with ratings

## Tools Used
- Python, Streamlit, VADER, TextBlob
- WordCloud, Pandas, Matplotlib

## How to Run Locally
pip install streamlit pandas numpy matplotlib textblob vaderSentiment wordcloud
streamlit run app.py
