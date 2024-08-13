## Summary

This project aimed to develop a movie recommendation system that suggests films based on user input. Leveraging Natural Language Processing (NLP) with NLTK, the system provides recommendations based on various attributes such as title, keywords, genre, cast, and director.

Key Features:

1. User Input Processing:

* Users input the title of a movie they like.

* The system parses this input to extract relevant information, including keywords, genre, cast, and director.

2. Data Extraction and Analysis:

* Utilized NLTK to analyze movie data and preprocess text for effective matching.

* Extracted features such as movie titles, genres, keywords, cast members, and directors from a dataset of movies.

3. Recommendation Algorithm:

* Implemented a recommendation algorithm that compares the user-provided movie with others in the dataset.

* Calculated similarity scores based on the extracted features: title similarity, keyword overlap, genre match, cast similarity, and director match.

4. Results Presentation:

* Generated a list of the top ten recommended movies.

* Each recommendation included a percentage match, indicating how closely it aligns with the user’s input movie based on the calculated similarity scores.

Outcome:

The system effectively identifies and suggests movies that match the user’s preferences. By integrating NLTK for text analysis and feature extraction, the recommendation engine delivers personalized movie suggestions, enhancing user experience with a focus on detailed matching criteria.
