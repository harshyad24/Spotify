
# 🎧 Spotify Music Analytics Dashboard (Power BI)
https://github.com/user-attachments/assets/8115301d-7ff7-4260-9608-b3240f0afeae

## 📖 Introduction

This project explores **Spotify music data** through an **interactive Power BI dashboard**. The goal was to uncover listening patterns, track popularity, and platform comparisons while practicing advanced **data cleaning, modeling, and visualization techniques** in Power BI.

The dashboard provides a visual story of how music evolves over time, when listeners are most active, and how tracks perform across platforms — all designed with a focus on clarity, interactivity, and aesthetics.

---

## 🎯 Project Objectives

* Analyze trends in music streaming over time
* Identify listening patterns by month and day
* Compare track popularity across platforms
* Create a visually appealing and user-friendly dashboard
* Apply Power BI data modeling and visualization best practices

---

## 📂 Dataset

The dataset includes Spotify track and artist metadata with fields such as:

* Track name & artist
* Release date
* Audio features (energy, danceability, etc.)
* Platform popularity (Spotify, Apple Music, Deezer)
* Total streams

---

## 🔧 Data Cleaning & Transformation (Power Query)

* **Error handling**: Removed errors in stream counts
* **Null replacement**: Replaced null values in keys with 0 to prevent dropping artist records
* **Custom date column**: Extracted and formatted dates for time intelligence
* **Calendar table**: Created using table view for year, month, and day breakdown
* **Modeling**: Established relationships between calendar and Spotify data for trend analysis

---

## 📊 Dashboard Features & Design

### 🔹 Heatmap Calendar

* Displays annual streaming activity across days and months
* Conditional formatting applied: darker green = higher streams, lighter green = lower streams
* Summarized by **bar charts** for total streams by month (bottom) and by day (right)

### 🔹 Popularity Matrix

* Matrix view showing track popularity across platforms
* Includes **track images** and playlist votes
* Conditional formatting: replaced numbers with **green bar visuals** to match Spotify UI design

### 🔹 Artist & Track Deep Dive

* Visual card highlighting top tracks (e.g., energy, danceability, key, mode, release date)
* Designed with transparent backgrounds and custom icons for a clean look

### 🔹 Trends Over Time

* Timeline visual showing how music popularity evolved across release years
* Connected via the calendar table for accurate time-based insights

---

## 🎨 Visualization & UI Enhancements

* Transparent backgrounds and subtle grid design for a clean layout
* Conditional formatting applied across visuals for consistency
* Customized color palette inspired by **Spotify green**
* Interactive slicers for filtering by artist, genre, and release date

---

## 🔍 Key Insights

* Clear listening “rhythms” emerge when analyzing streams by day and month
* Certain artists dominate popularity across multiple platforms
* Audio features such as energy and danceability strongly correlate with popular tracks
* Platform comparison highlights differences in playlist voting and track ranking

---

## 🛠 Tools & Technologies

* **Power BI** – Dashboard creation and visualization
* **Power Query** – Data cleaning and transformation
* **DAX** – Custom measures and calculated columns
* **Data Modeling** – Calendar relationship for time-based analysis

---

## 🏆 Conclusion

This project was more than just an analysis of Spotify data — it was an exercise in combining **data modeling, cleaning, and visualization best practices** to tell a story with music data.

Through Power BI, raw numbers were transformed into an intuitive dashboard that highlights patterns, compares platforms, and showcases what makes music resonate with listeners.

## 🎵 Features

### 📊 Core Analytics
- **Stream Statistics**: Total streams (489.46bn), total tracks (952), and average streams (514.14M)
- **Date Range Filtering**: Customizable date selection (01-01-1930 to 14-07-2023)
- **Track & Artist Filtering**: Dropdown filters for specific tracks and artists

### 📈 Advanced Visualizations
- **Streams by Release Date**: Interactive line chart showing streaming trends over decades
- **Rhythm of the Year**: Heat map calendar showing streaming patterns by day of week and month
- **Track Popularity Comparison**: Cross-platform analytics for Apple, Spotify, and Deezer playlists

### 🎶 Track Details Panel
- **Most Streamed Track**: Featured track display with album artwork
- **Audio Features Analysis**: Energy, Liveness, Danceability, Instrumentalness, and Speechiness metrics
- **Track Metadata**: Release date, key signature, and mode information
- **Integrated Music Player**: Play controls with track navigation

### 🌐 Multi-Platform Insights
- **Cross-Platform Analytics**: Compare track performance across streaming services
- **Playlist Penetration**: Visual comparison of track presence in different platform playlists

## 🚀 Technologies Used

- **Frontend**: Modern web technologies with interactive visualizations
- **Data Visualization**: Custom charts and heat maps for streaming analytics
- **APIs**: Spotify Web API, Apple Music API, Deezer API
- **UI/UX**: Spotify-inspired green theme with dark mode design
- **Charts**: Time-series analysis and calendar heat maps
- **Audio Analysis**: Integration with Spotify's audio features API

``

## 📧 Contact

Harsh Yadav - [@harshyad24](https://github.com/harshyad24)

Project Link: [https://github.com/harshyad24/Spotify](https://github.com/harshyad24/Spotify)


## 🌟 Example Data

The dashboard currently showcases analysis of:
- **Featured Track**: "Blinding Lights" by The Weeknd (3.7B+ streams)
- **Historical Range**: Music data spanning from 1930 to 2023
- **Audio Profile**: High energy (80%), low liveness (9%), moderate danceability (50%)
- **Cross-Platform Presence**: Analysis across Apple Music, Spotify, and Deezer playlists

---

⭐ Star this repository if you found it helpful!
