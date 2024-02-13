# Anime Recommender
This is an anime recommendation tool developed using Python and Jupyter Notebook, leveraging a Kaggle dataset.

## Introduction
This tool provides anime recommendations based on user input. It calculates similarities between anime titles using cosine similarity on user-item interaction data and recommends similar animes.

## Dataset
This tool uses a Kaggle dataset containing anime information and user ratings. You can find the dataset here: [Anime Recommendations Database](https://www.kaggle.com/datasets/CooperUnion/anime-recommendations-database?rvi=1)

## Installation

To use this tool, you need to have Python installed along with the following libraries:

- NumPy
- pandas
- scikit-learn (cosine similarity)
- fuzzywuzzy (handling typos using string matching)

You can install the required libraries using pip:

```bash
pip install numpy pandas scikit-learn fuzzywuzzy
