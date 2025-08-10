# 🎵 Visual Music Analyzer

**Visual Music Analyzer** is a Python-based data analysis project that explores music listening patterns using audio features like tempo, mood, energy, danceability, and genre trends. The goal is to uncover meaningful insights from music data and present them through visually engaging charts and summaries, creating a unique “musical fingerprint” for the listener.

---

## 📌 Project Overview
This project takes music metadata—either from the Spotify API or publicly available datasets—and analyzes how listening preferences change over time. It examines the relationship between different musical characteristics, identifies trends in genres and moods, and visualizes these patterns using a variety of statistical plots.

The analysis is designed to answer questions like:
- How does my mood in music change over time?
- What genres or artists dominate my playlists?
- How do tempo, energy, and valence correlate with each other?
- Are there seasonal or monthly trends in my music taste?

By the end, the project generates a set of visualizations and summaries that showcase the listener’s unique music preferences in a data-driven way.

---

## 🧰 Tools & Technologies
- **Python** – Main programming language for analysis and scripting
- **Pandas** – Data cleaning, manipulation, and aggregation
- **NumPy** – Numerical operations and statistical calculations
- **Matplotlib** – Custom visualizations and time-series plots
- **Seaborn** – Aesthetic statistical charts and correlation heatmaps
- **Spotify API** – (Optional) Live retrieval of music metadata
- **Jupyter Notebook** – Interactive development and documentation

---

## 📊 Features
- **Data Collection** – Import data from CSV or directly from Spotify API playlists/history
- **Data Cleaning** – Handle missing values, convert formats, and engineer new features like mood categories
- **Trend Analysis** – Explore how audio features evolve over weeks, months, and years
- **Genre & Artist Insights** – Identify most frequent artists and genre preferences
- **Mood Categorization** – Classify tracks into moods based on valence and energy
- **Correlation Analysis** – Display relationships between features via heatmaps
- **Visual Storytelling** – Present insights in clear, visually appealing plots

---

## 📈 Example Visualizations
- **Line Plots** – Tempo and mood progression over time
- **Bar Charts** – Most listened-to artists or genres
- **Scatter Plots** – Popularity vs. track length
- **Heatmaps** – Correlation between audio features
- **Violin/Box Plots** – Mood and energy distributions across genres

---

## 🎯 Outcomes
This project serves as both a personal music analytics tool and a portfolio piece showcasing skills in data analysis, visualization, and API integration. It demonstrates the ability to work with real-world datasets, uncover insights, and present findings in an engaging way.

On completion, the repository will include:
- A cleaned and processed dataset
- A Jupyter Notebook with the full analysis
- Exported visualizations in PNG format
- A detailed README with setup and usage instructions

---

## 🚀 Future Enhancements
- Build an **interactive Streamlit dashboard** for live exploration
- Integrate **machine learning** to predict mood or genre preferences
- Automate **real-time Spotify data sync** for continuous updates

---

## 📜 License
This project is licensed under the MIT License – feel free to use, modify, and distribute it.

--## 📑 Data Dictionary

| Column        | Meaning                                                                 | Planned Use                                                                 |
|---------------|-------------------------------------------------------------------------|------------------------------------------------------------------------------|
| **track_name** | Name of the song                                                        | For labeling charts and identifying tracks in top lists                     |
| **artist**     | Name of the performer or band                                           | Artist frequency analysis, popularity trends                                |
| **genre**      | Primary genre of the track                                              | Grouping songs for tempo/mood comparisons                                   |
| **release_date** | Date the song was released                                            | Time-based analysis (monthly/yearly trends)                                 |
| **tempo**      | Beats per minute (BPM)                                                  | Tempo distribution plots, average tempo over time                           |
| **valence**    | Measure of musical positiveness (0 = sad, 1 = happy)                    | Mood categorization, mood trend analysis                                    |
| **energy**     | Perceived intensity and activity level of a track                       | Energy vs mood comparisons, energy trends                                   |
| **danceability** | How suitable the track is for dancing based on tempo, rhythm, beat   | Danceability trends over time, genre comparisons                            |
| **duration_ms** | Length of the track in milliseconds                                   | Track length distribution, popularity vs length analysis                    |
| **popularity**  | Popularity score from Spotify (0–100)                                  | Comparing mainstream vs niche music trends                                  |

