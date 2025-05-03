# 🎧 Artist Streaming Data Analysis in Microsoft Excel

This project explores artist performance across major music streaming platforms using Microsoft Excel. By analyzing metrics such as total streams, playlist appearances, and release trends, we uncover what truly drives musical success in the online media space.

---

## 🧭 Introduction

### Objective of the Project
The aim is to identify performance trends among musical artists by analyzing streaming data across Spotify, Apple Music, Deezer, and Shazam. This includes understanding how playlist placement, musical features, and seasonal trends affect stream counts.

### Problem Being Addressed
With streaming being the dominant mode of music consumption, platforms and labels need insight into what makes a track go viral. Understanding the relationship between track metadata and performance helps stakeholders make strategic decisions.

### Key Datasets and Tools
- Track-level data with attributes: artist name, stream count, playlists, musical features
- Microsoft Excel features used:
  - Pivot Tables
  - Lookup Functions (e.g., VLOOKUP)
  - Charts (line, bar, pie)

---

## 📊 Story of the Data

- **Data Source**: Aggregated from music streaming platforms and internal analytics.
- **Data Structure**: Each row represents a track, including stream counts, playlist appearances, BPM, key, and mode.
- **Important Features**:
  - `Track Name`, `Artist Name`: Identifiers for performance
  - `Streams`: Core success metric
  - `Mode`, `Energy`, `Danceability`: Musical traits analyzed
- **Data Limitation**:
  - Platform bias: Spotify data appears more extensive than Deezer or Shazam.

---

## 🔄 Data Preprocessing

- Cleaned duplicate entries and verified streaming consistency
- Filled missing playlist entries with zeros
- Aggregated stream counts by artist, track, and month
- Split features:
  - **Independent Variables**: Track Name, Artist Name, Mode
  - **Dependent Variables**: Streams, Playlist Entries, Musical Traits

---

## 🔍 Pre-Analysis Observations

- January and May had the highest stream activity
- Majority of tracks are in major key (550 vs 403 minor)
- Artists like The Weeknd, Taylor Swift, and Ed Sheeran dominate stream charts

---

## 📈 In-Analysis Highlights

### Potential Insights
- Playlist inclusion (especially Spotify) correlates with higher stream counts
- High-energy tracks in major keys may perform better
- Seasonal trends suggest timing releases for maximum exposure

### Recommendations
- Prioritize playlist strategies for major key, upbeat songs
- Focus marketing during January and May
- Budget more for high-performing artists (e.g., The Weeknd)

### Excel Techniques Used
- Pivot Tables for aggregation
- VLOOKUP to merge track-playlist data
- Charts for visual storytelling

---

## ✅ Post-Analysis Findings

- **Top Track**: *Blinding Lights* – 3.7B+ streams
- **Top Artist**: The Weeknd – 14.1B+ streams
- **Top Months**: January (134) and May (128)
- Playlist appearances strongly correlate with high streams

---

## 📊 Visuals Created in Excel

- Bar Chart: Top 5 Artists by Total Streams
- Line Graph: Monthly Stream Trends
- Stacked Bar: Playlist Appearances per Track
- Pie Chart: Distribution of Modes (Major vs Minor)

![Confirmed Dashboard 5](https://github.com/user-attachments/assets/0897d3c1-c08e-4fce-92f1-4d0fe6bd88eb)

---

## 📌 Final Recommendations

- Push high-energy, major key tracks into prominent playlists
- Time key releases for high-performing months (Jan & May)
- Build cross-platform playlist strategies for maximum reach

---

## 🧾 Conclusion

### Key Learnings
- Playlist placement, artist branding, and track musicality influence success
- Spotify is the dominant force for visibility and streams

### Future Exploration
- Add user engagement metrics (skip rate, listening time)
- Include genre-based or regional segmentation

---

## 📎 License

This project is for educational and non-commercial use. Contact me for collaboration or further analysis opportunities.
