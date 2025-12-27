#  Spotify Lyric Search

##  Project Overview
This project identifies the song title and artist using a small snippet of lyrics.
It uses Natural Language Processing (NLP) and machine learning techniques.

##  Technologies Used
- Python
- Pandas, NumPy
- NLTK
- Scikit-learn
- TF-IDF Vectorizer
- Cosine Similarity

## Dataset
Spotify songs dataset containing:
- Song title
- Artist name
- Lyrics

## Methodology
1. Text preprocessing (lowercase, punctuation removal, stop-word removal)
2. Feature extraction using TF-IDF
3. Similarity comparison using cosine similarity
4. Prediction of song and artist

## How to Run
```bash
pip install -r requirements.txt
jupyter notebook lyric_search.ipynb
