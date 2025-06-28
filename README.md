Movie Recommendation System

This peoject is a movie recommendation system that suggests similar movies based on content features like genre, cast, director, and plot overview. It uses natural language processing and cosine similarity to recommend movies related to a user’s favorite.

## 🔍 How It Works

1. Data Preprocessing: Combines TMDB movie metadata from two CSV files.
2. Feature Engineering: Extracts and merges keywords, cast, genres, and director into a single text feature (`tags`).
3. Vectorization: Applies `CountVectorizer` to convert text into numerical features.
4. Similarity Matching: Uses cosine similarity to find and recommend the top 5 most similar movies to the input title.
