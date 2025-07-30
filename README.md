# 🎵 Music Genre Predictor

A basic machine learning project that classifies songs into genres using audio features like tempo, danceability, acousticness, and more.

## 🧠 Model
- Random Forest Classifier
- StandardScaler for feature scaling
- LabelEncoder for target encoding

## 📊 Dataset
Dataset sourced from Kaggle (cleaned for training and testing)

## 🔍 Sample Prediction
```python
example_input = {
  'popularity': 40,
  'acousticness': 0.03,
  'danceability': 0.75,
  'duration_ms': 200000,
  'energy': 0.8,
  'instrumentalness': 0.2,
  'liveness': 0.1,
  'loudness': -5.0,
  'speechiness': 0.05,
  'tempo': 120.0,
  'valence': 0.7
}
