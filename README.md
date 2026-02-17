# Spotify Music Streaming Analysis 🎵📊

## Overview
This project analyzes Spotify track-level audio features to understand how musical characteristics influence popularity across genres. The goal was not only to extract insights, but to present them through a **clean, premium-quality Power BI dashboard** suitable for portfolio and interview discussions.

The project follows a realistic analytics workflow, combining Python-based data preparation with interactive BI visualization.

---

## Tools & Technologies
* Python (pandas, numpy)
* Jupyter Notebook
* Power BI Desktop
* CSV-based data pipeline

---

## Dataset
* Spotify track-level dataset with audio features
* Includes popularity scores and genre classifications
* Focused on audio attributes such as danceability, energy, valence, tempo, and acousticness
* Dataset does not include release year or explicit-content indicators

---

## Project Workflow
1. Raw Spotify dataset imported into Python
2. Data cleaned and prepared using pandas:
   - Removed null values and duplicates
   - Selected analysis-ready audio features
3. Clean dataset exported as CSV
4. Interactive dashboard developed in Power BI using a custom dark theme

---

## Dashboard Design Philosophy
The dashboard was designed with a **product analytics mindset**, prioritizing clarity, hierarchy, and aesthetic restraint.

### Key design choices:
* Dark premium theme inspired by Spotify branding
* Restricted color palette for visual consistency
* Clear visual hierarchy:
  - KPI cards for instant context
  - Central scatter plot as the main analytical focus
  - Supporting bar charts for genre comparison
* Minimal gridlines, borders, and clutter to reduce visual noise

---

## Dashboard Features
* KPI cards showing total tracks and average popularity
* Scatter plot visualizing danceability vs popularity
* Bar charts comparing genres by popularity and energy
* Interactive slicers for genre and popularity range
* Fully responsive and filter-driven exploration

---

## Key Insights
* Tracks with higher danceability and energy tend to show higher popularity
* Popularity varies significantly by genre
* Acoustic and instrumental-heavy tracks generally cluster at lower popularity levels

---

## Future Improvements
* Integrate Spotify Web API for real-time data updates
* Add correlation analysis and clustering in Python
* Expand dashboard with drill-through and tooltip pages

---

## Author
Harini S 
Data Analytics Portfolio Project
