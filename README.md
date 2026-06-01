# Movie Recommender System 

A Movie Recommender System built using **Machine Learning** that suggests movies to users based on similarity and recommendation algorithms. This project helps users discover movies according to their interests and viewing preferences.

---



##  Features
- **Content Based Recommender System:** Based on what user previously liked by user.
- **Modern UI/UX:** Clean user interface using Streamlit.
- **API Integration:** TMDB Dataset and API's

---

##  Tech Stack
- **Language:** Python 
- **ML Stack:** Scikit-Learn, Vectorizer
- **Framework:** Streamlit
- **Environment Management:** Virtualenv, VS Code

---

##  Project Structure
```text
movie_recommender_system/
├── .venv     
├── movie_recommend_dataset
|  ├── tmdb_5000_credits.csv
|  └── tmdb_5000_movies.csv             
├── app.py             
├── movie_dict.pkl
├── movies.pkl
├── procfile
├── README.md
├── requirements.txt  
├──.gitignore  
├── similarity.pkl  
└── setup.sh   
         
```

---

## Dataset
- [TMDB 5000 Movie Dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)


---

##  Future Enhancements 
- **Collaborative filtering:** Predict a user's interests by collecting preferences from many users. 
- **Hybrid Recommendation System:** Combines multiple algorithms (such as collaborative filtering, content-based filtering, and deep learning) into a single framework.
- **Deployment on cloud platforms:** Deploy full website on cloud platforms
