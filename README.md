# Spotify-Songs-EDA-and-Hit-Prediction
Exploratory Data Analysis and machine learning model on Spotify dataset to analyze audio features (danceability, energy, tempo, etc.) and predict whether a song will become a hit based on its popularity score.
This project leverages a large Spotify dataset to explore the relationships between audio features and song popularity. Through detailed exploratory data analysis (EDA), we visualize trends in danceability, energy, tempo, and other track characteristics. We then define a “hit” song (popularity ≥ 70) and build a Random Forest Classifier to predict hit songs using audio features. The project demonstrates skills in data wrangling, visualization, feature engineering, and machine learning model development.
# 🎵 Spotify Songs EDA and Hit Prediction

## 📌 Project Overview
This project analyzes Spotify tracks dataset to uncover patterns in audio features such as **danceability, energy, tempo, acousticness, and valence**, and uses machine learning to predict whether a song will be a **hit** based on its popularity score.

The goal is to answer:
- What audio features correlate most with popularity?
- Can we build a model to classify a song as a hit or not?

---

## 📂 Dataset
We used the [Spotify Tracks Dataset](https://github.com/gabminamedez/spotify-data) containing 160K+ songs with audio features and popularity scores.

Key features used:
- `danceability`  
- `energy`  
- `tempo`  
- `valence`  
- `acousticness`  
- `instrumentalness`  
- `speechiness`  
- `liveness`  
- `loudness`  
- `popularity`

---

## ⚙️ Methodology
1. **Data Cleaning** – Handle missing values and select relevant features.  
2. **Exploratory Data Analysis (EDA)** – Visualize popularity distribution, feature correlations, and pairplots.  
3. **Hit Definition** – Songs with popularity ≥ 70 are considered **hits**.  
4. **Model Training** – Random Forest Classifier to predict hit songs.  
5. **Evaluation** – Classification report, confusion matrix, and feature importance.  

---

## 📊 Results
- Popularity distribution shows most tracks cluster below 50 popularity.  
- Strong correlations observed between **energy, loudness, and danceability**.  
- Random Forest achieved good classification performance.  
- Feature importance shows **energy, loudness, and danceability** are strong predictors of hit songs.  

---

## 🚀 Tech Stack
- Python 🐍  
- Pandas & NumPy  
- Matplotlib & Seaborn  
- Scikit-learn (Random Forest Classifier)  

---

## 📈 Example Visualizations
- Popularity distribution histogram  
- Correlation heatmap  
- Feature importance plot  

---

## ▶️ How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/spotify-hit-prediction.git
   cd spotify-hit-prediction
