# 🎵 Features of the Most Streamed Songs of 2024

> **Spotify Data Visualization Project** | Master's in Data Science  
> Analyzing audio features, streaming patterns, and artist trends using Tableau

![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=Tableau&logoColor=white)
![Data Visualization](https://img.shields.io/badge/Data%20Visualization-1DB954?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)

---

## 📌 Project Overview

This project was developed as part of the Master's in Data Science program by **Team DataBeasts**. Acting as a data consultancy for music industry professionals, we analyzed the features behind the most streamed Spotify songs of 2024 to uncover what makes a hit song.

**Goal:** Empower artists, producers, and industry professionals to make informed creative and strategic decisions using data-driven insights.

---

## 👥 Team

| Name | Role |
|------|------|
| Matteo Ciuffreda | Data Analyst & Visualization |
| Emmanuel Ampah | Data Analyst & Visualization |
| Sara Rizzi | Data Analyst & Visualization |
| Stephen Yaboah | Data Analyst & Visualization |

---

## 📊 Dataset

The dataset was built by merging **4 distinct Kaggle datasets**:

| Dataset | Key Features |
|--------|-------------|
| [Spotify's Most Streamed Songs 2024](https://www.kaggle.com/) | Song names, artist names, total streams, daily stream counts |
| [Spotify Songs](https://www.kaggle.com/) | Audio features (energy, danceability, valence) |
| [Spotify Music Dataset](https://www.kaggle.com/) | Song popularity scores |
| [Top Spotify Songs in 73 Countries](https://www.kaggle.com/) | Global popularity data |

The merged dataset covers globally popular tracks and their characteristics including loudness, liveness, acousticness, and BPM.

---

## 🔍 Key Research Questions

1. **Which artists and songs dominate Spotify streaming?** Identifying top performers and the correlation between stream count and popularity score.
2. **What audio features define hit songs?** Analyzing danceability, energy, and acousticness across popularity tiers.
3. **Does song length affect success?** Examining whether popular songs tend to be shorter or longer.

---

## 📈 Main Findings

### 🎤 Artists & Songs
- **Taylor Swift** leads with 30B+ streams and 33 songs in the dataset — the largest catalog of any top artist.
- **The Weeknd** is the only artist with **two songs** in the Top 10 most streamed tracks ("Blinding Lights" and "Starboy").
- **Blinding Lights** tops the chart with over **4.5 billion streams**.
- Popularity score and stream count show a **positive correlation**, but notable outliers exist — some songs accumulate streams through playlists or viral moments without maintaining high current popularity.

### 🎵 Audio Features
- **Danceability** is consistently high across all popularity tiers (~0.64–0.66) — it matters, but it's not the deciding factor.
- **Acousticness** is generally low among popular songs, but high-popularity songs show a slightly higher acoustic value (~0.27) compared to low-popularity ones (~0.17).
- **Energy** levels are high overall, but the most popular songs surprisingly tend to have slightly **lower energy** than the rest.
- The optimal audio profile for a hit: **danceability ≈ 0.3**, **acousticness ≈ 0.7**, **energy ≈ 0.2**.

### ⏱️ Tempo & Duration
- Most streamed songs fall in the **90–130 BPM** range, with 90 and 120 BPM being the most frequent.
- Optimal song duration is **~210 seconds (3:30 min)**. Songs between 200–240 seconds score highest in popularity.

---

## 🛠️ Tools & Technologies

- **Tableau Desktop** — Dashboard design and interactive visualizations
- **Data Wrangling** — Dataset merging and preprocessing
- **Kaggle** — Data source

---

## 📁 Repository Structure

```
spotify-most-streamed-2024/
│
├── Spotify-project.twbx          # Tableau packaged workbook (open with Tableau Desktop/Public)
├── Spotify-project.twb           # Tableau workbook file
├── report/
│   └── Features_of_the_most_streamed_songs_of_2024.pdf   # Full slide deck & analysis
└── README.md
```

---

## 🚀 How to Open the Dashboard

1. Download [Tableau Public](https://public.tableau.com/en-us/s/download) (free) or use Tableau Desktop.
2. Clone this repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/spotify-most-streamed-2024.git
   ```
3. Open `Spotify-project.twbx` with Tableau.

> Alternatively, view the full analysis in the [PDF report](report/Features_of_the_most_streamed_songs_of_2024.pdf).

---

## 📷 Dashboard Preview

<img width="1422" height="837" alt="image" src="https://github.com/user-attachments/assets/6dad91ae-341e-4474-b6c3-beff227569b0" />


---

## 📚 Related Projects

Check out my other Data Science projects:
- [🔗 Project 2 Name](link)
- [🔗 Project 3 Name](link)

---

## 📄 License

This project is for academic and portfolio purposes. Data sourced from public Kaggle datasets.
