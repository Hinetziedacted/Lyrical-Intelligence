#  Lyrical Intelligence: Song Lyrics Sentiment Analysis with Python

A beginner-friendly NLP project that uses the VADER sentiment analyzer to explore emotional tone in modern song lyrics.

##  Files Included
- `lyrics.csv`: Input dataset of 10 well-known tracks
- `cleaned_lyrics.csv`: Output file with sentiment scores
- `Lyrical_Intelligence.ipynb`: Google Colab notebook with full processing + visualization

## Features
- Text cleaning (punctuation removal, lowercasing)
- Sentiment analysis using VADER (compound scores)
- Histogram visualization using Matplotlib
- Live custom lyric testing with `get_lyric_sentiment()`

##  How to Use
1. Open the `.ipynb` file in Google Colab
2. Upload `lyrics.csv` when prompted
3. Run cells top to bottom
4. View the histogram and download `cleaned_lyrics.csv`
5. Try your own lyrics with the live tester

##  Dependencies
```bash
pip install pandas matplotlib nltk vaderSentiment
