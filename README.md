🎬 Movie Recommender System (Content-Based)

This project is a Content-Based Movie Recommender System that suggests similar movies based on their content such as genres, keywords, cast, and overview.
It uses text similarity techniques instead of training a machine learning model.

🔁 Project Flow

Data → Processing → Recommendation Logic → Web Application → Deployment

Data
Movie metadata including title, genres, keywords, cast, and overview.

Processing

Data cleaning and preprocessing

Important features combined into a single tags column

Recommendation Logic

Text vectorization using Bag of Words

Numerical representation with CountVectorizer

Similarity calculation using Cosine Similarity

Web Application

User-friendly interface to select a movie

Displays top recommended similar movies

Deployment

Deployed as a web application for real-time recommendations

🧠 Types of Recommender Systems

There are three main types of recommender systems:

Content-Based Filtering

Collaborative Filtering

Hybrid Recommender System

👉 This project implements Content-Based Filtering.

🎯 Content-Based Recommendation

The system recommends movies by comparing movie content, not user behavior.
Movies with similar tags are recommended together.

⚙️ Techniques Used (No Model Training)

This project does not train a machine learning model.
Instead, it relies on classical NLP and similarity-based techniques:

Bag of Words (BoW)
Converts text into word frequency vectors.

CountVectorizer
Transforms textual data into numerical vectors.

Cosine Similarity
Measures similarity between movies based on vector angles.

🛠️ Tech Stack

Python

Pandas

NumPy

Scikit-learn

Streamlit

🚀 Features

Simple and efficient recommendation logic

Beginner-friendly implementation

Easy to extend with collaborative or hybrid approaches

📌 Future Improvements

Add Collaborative Filtering

Implement Hybrid Recommendation

Improve UI and scalability

📎 How to Run
pip install -r requirements.txt
streamlit run app.py

📖 Learning Outcome

This project demonstrates how recommendation systems work internally and is ideal for beginners learning Machine Learning and NLP concepts.
