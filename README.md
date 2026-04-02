# 🎧 Spotify Tracks Analysis Dashboard (Power BI)

## 📌 Project Overview

This project is an interactive **Power BI dashboard** built to analyze Spotify tracks using audio features and popularity metrics.
The goal is to uncover insights about **what makes songs successful**, understand **artist performance**, and explore **music characteristics** such as mood, energy, and rhythm.

---

## 🎯 Objectives

* Analyze track popularity and identify **hit songs**
* Explore relationships between audio features (energy, danceability, valence, etc.)
* Build **artist-level profiles** for deeper insights
* Provide **business-driven insights** for music trends

---

## 📊 Dataset Description

The dataset contains Spotify track-level information, including:

* **Track Info**: track name, album, artists
* **Popularity**: score from 0–100
* **Audio Features**:

  * Danceability
  * Energy
  * Valence (mood)
  * Loudness
  * Instrumentalness
  * Speechiness
* **Music Theory**:

  * Key (C, D, E, etc.)
  * Mode (Major / Minor)
* **Duration**: track length in milliseconds
* **Genre**: track category

---

## 📈 Dashboard Structure

### 🟢 Page 1: Overview

* KPIs: Total Tracks, Albums, Artists, Avg Popularity
* Top Artists & Top Genres
* Popularity Distribution
* Tracks by Musical Key
* Duration vs Popularity (Scatter Plot)
* Key Insights Panel

---

### 🟢 Page 2: Artist Analysis

* Artist Slicer (with search & Top N filtering)
* KPIs: Avg Energy, Danceability, Duration, Hit Rate
* Audio Profile Comparison
* Track-Level Table

#### 🆕 Added Analysis:

* 🍩 **Mood Distribution** (based on Valence, Energy, Mode)
* 🍩 **Live Category** (based on Liveness)
* 🍩 **Rhythm Profile** (based on Danceability & Energy)

---

## 🧠 Key Features & Calculations

### 🔹 Hit Rate

Percentage of tracks with popularity ≥ 70:

Hit Rate = (Number of Hit Songs) / (Total Songs)

---

### 🔹 Feature Engineering

* Categorized continuous variables:

  * Danceability → Low / Medium / High
  * Energy → Low / Medium / High
  * Valence → Mood categories
* Converted duration from milliseconds to minutes
* Transformed mode (0/1) → Minor / Major

---

## 📌 Key Insights

* High-energy and danceable tracks tend to have higher popularity
* Certain genres dominate in both volume and performance
* Artist performance varies significantly in terms of consistency (Hit Rate)
* Mood and rhythm profiles provide deeper understanding of track characteristics

---

## 🛠 Tools Used

* Power BI (Data Modeling, DAX, Visualization)
* DAX (Measures, Calculated Columns, KPIs)

---

## 🚀 Future Improvements

* Add predictive model for hit songs
* Integrate time-based trends
* Enhance user-driven interactivity (dynamic parameters)


