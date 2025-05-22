# Movie Recommendation System

A collaborative filtering movie recommendation system built using **FastAI**. It predicts user ratings and recommends similar movies using learned embeddings.

## Dataset

This project uses the [MovieLens 1M Dataset](https://grouplens.org/datasets/movielens/1m/), which contains:
- 1 million movie ratings from 6,000 users on 4,000 movies
- Metadata like movie titles and genres

**Download the dataset** and extract it into the project folder:


## Features

- Predicts user ratings for any movie
- Recommends similar movies using learned embeddings
- Interactive UI with **Gradio**

## Requirements
Main dependencies:
- fastai
- torch
- pandas
- gradio (for UI)
- scikit-learn


## Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/eurysee/movie-recommender.git
```
```bash
cd movie-recommender
```

### 2. Create and Activate Virtual Environment
```bash
python -m venv venv
```
- On macOS/Linux:
```bash
source venv/bin/activate  
```
- On Windows (Command Prompt):
```bash
venv\Scripts\activate.bat
```

- On Windows (PowerShell):
```bash
venv\Scripts\Activate.ps1
```

### 3. Install Requirements

```bash
pip install -r requirements.txt
```

### 4. Run the Jupyter Notebook

## Project Overview
- Uses FastAI’s collab_learner for collaborative filtering.
- Learns latent embeddings for users and movies.
- Uses cosine similarity between movie embeddings to recommend similar movies.
- Predicts ratings using the dot product of user and movie vectors.

## Example Use Cases
- Predict rating a user would give to a specific movie.
- Get recommendations for movies similar to Star Wars: Episode IV - A New Hope (1977).
- Learn how collaborative filtering works using embeddings.
