# Personalized-Movie-Recommendations-Based-on-Genre-Preferences
This project builds a movie recommendation system that suggests movies based on a user’s favorite genres. It uses Python and SQL to collect, clean, store, and visualize data, and a basic algorithm to generate movie suggestions.

Dataset

The dataset includes movie titles, genres, ratings, and release years. It can be sourced from IMDb or Kaggle.

Setup Instructions

1. Create a Virtual Environment
     `python -m venv venv`
3. Activate the Virtual Environment
   
	•	On macOS/Linux:

     `source venv/bin/activate`
   

	•	On Windows:

     `venv\Scripts\activate`
   
5. Install Required Libraries
   
    `pip install -r requirements.txt`
   
7. Run the Project

   Open the movie_recommendations.ipynb file in a Jupyter notebook and run the code to start generating movie recommendations.

Project Structure

```
/movie-recommendation
    /data
        movies.csv         # Movie dataset
        user_profiles.csv  # Synthetic user profiles
    /notebooks
        movie_recommendations.ipynb  # Notebook for the recommendation system
    requirements.txt    # Dependencies
    README.md            # This file

```

Technologies Used

  - Python
  - SQLite
  - Pandas
  - Matplotlib & Seaborn
