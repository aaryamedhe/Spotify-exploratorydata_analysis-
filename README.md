# 🎵 Spotify Music Analysis
### Uncovering Hidden Music Personalities Using 114,000 Tracks

**Author:** Aarya Medhe  
**Dataset:** [Spotify Tracks Dataset — Kaggle](https://www.kaggle.com/datasets/maharshipandya/-spotify-tracks-dataset)  
**Tools:** Python, Pandas, Matplotlib, Seaborn, Scikit-learn

---

## 🎯 Objective

This project explores 114,000 Spotify tracks across 114 genres to answer one central question:

> **"What kind of music does the world actually listen to — and can we find hidden music personalities using data?"**

---

## 📊 Dataset Overview

| Attribute | Value |
|---|---|
| Original dataset size | 114,000 songs |
| After cleaning | 80,393 songs |
| Genres | 114 |
| Columns | 21 |
| Popularity Range | 0 – 100 |

---

## 📁 Project Structure

```
spotify-music-analysis/
│
├── Spotify_analysis.ipynb   # Main notebook with all analysis
├── dataset.csv              # Raw dataset from Kaggle
└── README.md                # You are here
```

---

## 🔍 What's Inside the Notebook

| Section | What It Does |
|---|---|
| 1. Setup & Imports | Loads all Python libraries needed |
| 2. Load the Dataset | Reads the CSV file and inspects the data |
| 3. Data Cleaning | Removes missing values, duplicates and zero popularity songs |
| 4. The Popularity Problem | Visualizes how rare it is to become popular on Spotify |
| 5. The Mood Map | Plots every song by energy and happiness to find mood patterns |
| 6. The Danceability Story | Checks whether danceable songs are more popular |
| 7. Artist Analysis | Finds most prolific and most popular artists |
| 8. Key Findings | Narrative summary of all discoveries |

---

## 🔑 Key Findings

**1. Getting popular on Spotify is rare**
Only 3.9% of songs ever cross a popularity score of 70.
55% of all songs sit in the low tier — below a score of 40.

**2. The world prefers high energy music**
The most popular songs cluster in the Happy/Hype zone —
high energy and happy sounding tracks consistently outperform calm ones.

**3. Danceability matters — but only a little**
Average danceability rises from 0.550 in low tier songs to 0.622 in super hits.
The gap is small, meaning danceability contributes but cannot make a hit on its own.

**4. Prolific artists are not always the most popular**
George Jones has the most songs in our dataset (260) but having
the most songs does not mean being the most popular artist.

**5. The big insight**
Audio features describe how a song sounds but the real difference
between an average track and a hit comes from external factors like
artist recognition, playlist placement, and release timing.

---

## 🛠️ How to Run This Project

**Google Colab (easiest)**
1. Download `Spotify_analysis.ipynb`
2. Go to [colab.research.google.com](https://colab.research.google.com)
3. Upload the notebook
4. Upload `dataset.csv` to the Colab files panel
5. Run all cells top to bottom


---

## 📦 Libraries Used

| Library | Purpose |
|---|---|
| `pandas` | Loading and cleaning data |
| `matplotlib` | Building charts |
| `seaborn` | Styling and visualizations |
| `scikit-learn` | K-Means clustering |

---

## 🚀 What I Would Do Next

- Add a popularity prediction model using Random Forest
- Analyze how music trends have changed over time
- Build a song recommender based on audio features
- Explore whether explicit songs perform better than clean ones

---

## 📬 Connect With Me

Made with 🎵 and Python by **Aarya Medhe**
