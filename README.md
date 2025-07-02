# Movie Predictor Application using Machine Learning

The Movie Predictor Application is a content-based movie recommendation system that helps users discover new movies they'll love. By entering the name of a movie they like, the app analyzes its key features—such as keywords, cast, genres, and director—and returns five similar movies.
It does this by transforming movie metadata into text vectors and comparing them using cosine similarity, identifying films with the highest feature overlap.

# Key Features:
- Easy to Use: User enters the name of any movie they like.
- Personalized Recommendations: Returns five movies most similar in theme, genre, and cast.
- Intelligent Matching: Finds recommendations even for lesser-known titles if metadata is available.
- Data-Driven: Built on movie datasets containing rich descriptive features.

Whether you want to find movies with a similar vibe to your favorite blockbuster or discover hidden indie gems with a comparable cast or genre, the Movie Predictor Application is your personal movie matchmaker.

# Version Information
- Python (pandas, numpy): For data loading, cleaning, and manipulation.
- CountVectorizer (scikit-learn): Converts combined text features into numerical vectors using bag-of-words representation.
- Cosine Similarity (scikit-learn): Computes similarity between movies based on their vectorized features.
- Content-Based Filtering: Uses movie metadata (keywords, cast, genres, director) to determine similarity between movies.
- CSV Data Source: Movie dataset containing columns like title, index, keywords, cast, genres, and director.
