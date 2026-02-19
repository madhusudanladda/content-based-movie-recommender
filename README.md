# 🎬 Movie Recommendation System

A content-based movie recommendation web application built using Python, Flask, and Scikit-learn.  
The system recommends similar movies using NLP-based vectorization and cosine similarity.


## 🚀 Features

- Content-based movie recommendation
- NLP vectorization (TF-IDF / CountVectorizer)
- Cosine similarity for ranking
- Flask backend integration
- Clean web interface (HTML/CSS)
- Git version controlled project


## 🧠 How It Works

1. Movie metadata is processed and combined into a single feature column (`tags`).
2. Text data is vectorized using NLP techniques.
3. Cosine similarity is calculated between movies.
4. When a user selects a movie, the system returns the top 5 most similar movies.


## 🛠️ Tech Stack

- Python
- Flask
- Pandas
- NumPy
- Scikit-learn
- HTML / CSS
- Git


## 📂 Project Structure

movie-recommendation-system/

│

├── app.py

├── requirements.txt

├── templates/

│ └── index.html

├── movie_recommender_model.ipynb



## ▶️ Run Locally

1. Clone the repository

git clone https://github.com/yourusername/content-based-movie-recommender.git

cd content-based-movie-recommender


2. Install dependencies

pip install -r requirements.txt


3. Run the application

python app.py


4. Open in browser:

http://127.0.0.1:5000


## 📌 Future Improvements

- Add movie posters using TMDB API
- Improve recommendation quality using TF-IDF
- Add search functionality
- Deploy the application online

## ⚠️ Important

The `similarity.pkl` file is not included in this repository due to GitHub file size limitations.

Before running the Flask app, please execute the notebook:

`movie_recommender_model.ipynb`

This will generate the required model files (`movies.pkl` and `similarity.pkl`) needed to start the application.


## 👨‍💻 Author

Madhusudan Ladda  
B.Tech Computer Science  
