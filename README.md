Project Overview: This project implements a text-identification system that predicts the song and title and Artist when given a small snippet of song lyrics or text.

Overviw: 
    Identify the most relevent song and artist from a lyrics snippet
    Apply text preprocessing, tokenization, and deep learning
    Use TensorFlow as required in the problem statement.

Technologies
     Python
     TensorFlow
     Pandas & Numpy
     NLKT
     Jupyter Notebook

Methodology
     Convert the input snippet into a vector embedding
     Compute cosine similarity between the snippet embedding and all song embeddings
     Select the song with the highest similarity score.

Return
     Song Time
     Artist Name
     Similaity Score

     Model Evaluation
          Random lyric snippets were tested from the dataset
          Accuracy achived: 80-85%
          performance depends on dataset quality