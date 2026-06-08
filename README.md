# What Makes a Song Go Viral?
## Spotify Data Analysis using Python & AI

##  About This Project
A statistical and AI-powered analysis of what makes 
songs go viral on Spotify.

Built as Part 7 of my **Statistics × AI × Future World** 
series on LinkedIn.

##  What This Project Does
- Analyzes thousands of real Spotify songs
- Compares viral vs normal songs statistically
- Predicts viral potential using Random Forest AI
- Reveals the mathematical formula behind viral music

## Key Findings
-  AI predicts viral songs with **94.4% accuracy**
-  Danceability is the #1 viral factor
-  High energy songs get shared more
-  Valence (happiness) score 0.6–0.8 = sweet spot
-  Tempo sweet spot: 100–130 BPM

##  The Viral Formula
Viral Song = Right BPM + High Valence 
           + Danceability + High Energy

##  Tech Stack
- Python (pandas, numpy, matplotlib, seaborn)
- Scikit-learn (Random Forest Classifier)
- Spotify Songs Dataset (TidyTuesday)
- Google Colab

##  Dashboard Preview
![Viral Songs Analysis](viral_songs_analysis.png)
![Feature Importance](viral_feature_importance.png)

## Project Structure
spotify-viral-analysis/
│
├── viral_songs_analysis.ipynb  ← Main notebook
├── viral_songs_analysis.png    ← Dashboard
├── viral_feature_importance.png ← AI insights
└── README.md



This project is for educational purposes only.
Dataset sourced from TidyTuesday open data.
