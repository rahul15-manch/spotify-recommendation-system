# 🎵 Spotify Recommendation System

A machine learning-based recommendation system that suggests songs based on user preferences and listening history. This project uses audio features, metadata, and collaborative filtering techniques to generate personalized Spotify music recommendations.

## 🚀 Features

- 🎧 Recommend songs based on audio features (tempo, energy, danceability, etc.)
- 📈 Content-Based Filtering using Spotify's audio features
- 🤝 Collaborative Filtering using user-song interaction data
- 🔍 Search and explore songs by genre, artist, or track


## 🛠️ Tech Stack

- Python
- Pandas, NumPy, Scikit-learn
- Flask (for web interface)
- Seaborn/Matplotlib (for visualizations)

## 📁 Project Structure

spotify-recommendation-system/
│
├── data/ # Dataset files
├── notebooks/ # Jupyter notebooks for EDA and modeling
├── app/ # Web app code (if using Streamlit)
├── models/ # Saved ML models
├── utils/ # Helper functions
├── requirements.txt # Python dependencies
├── README.md # Project overview
└── main.py # Main script to run the system


## 📊 Dataset

The project uses either:
- A **custom dataset** of Spotify tracks with audio features, or
- Data retrieved using the **Spotify Web API** via Spotipy

Features include:
- `track_name`, `artist`, `popularity`, `tempo`, `energy`, `valence`, `danceability`, etc.
Install Dependencies:
-pip install -r requirements.txt
Run the app:
-python app.py


