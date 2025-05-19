# From Vinyl to Streaming – The Sound Revolution

**Interactive Power BI Report**  
Exploring the evolution of popular music—from vinyl records in the 1980s to today’s streaming era—using Spotify audio features and metadata.

---

## Table of Contents

1. [Project Overview](#project-overview)  
2. [Report Pages & Key Visuals](#report-pages--key-visuals)  
3. [Data Source & Preparation](#data-source--preparation)  
4. [How to Use](#how-to-use)  
5. [File Structure](#file-structure)  
6. [Authors & Acknowledgments](#authors--acknowledgments)  
7. [License](#license)  

---

## Project Overview

Between 1980 and 2020, the way we consume music has transformed dramatically—from vinyl and cassettes to CDs and finally to on-demand streaming. This Power BI report:

- Quantifies changes in track counts, artist diversity and audio characteristics over four decades.  
- Highlights landmark industry events (e.g. “Loudness Wars,” Spotify’s 2012 launch).  
- Enables both period-level and artist-specific deep dives.  

_Instituição: NOVA Information Management School_  
_Course: Data Visualization_  
_Powered by: Spotify Audio Features API_

---

## Report Pages & Key Visuals

### 1. **The Sound Revolution (Overview)**
- **Period Selector**: Toggle between **1980–1999** and **2000–2020**.  
- **Top KPIs**:  
  - Number of tracks released  
  - Number of unique artists  
- **Explicit Content**: Dot matrix showing share of explicit tracks.  
- **Energy Gauge**: Average “energy” score on a 0–1 scale.  
- **Trend Lines**:  
  - **Average Duration** (ms) by year  
  - **Average Loudness** (dB) by year  
- **Track Length Distribution**: “How many tracks under 4 min?”  
- **Speechiness Donut**: Share of “speechy” tracks by period.

### 2. **Artist’s Evolution**
- **Artist Picker**: Dropdown menu to select any artist in the dataset.  
- **Artist Profile**: Album-cover style image and summary KPIs:  
  - Total tracks  
  - Avg. popularity  
  - Avg. danceability  
  - Avg. mode  
- **Energy Gauge**: Artist’s average energy.  
- **Tempo Bubbles**: Average tempo by release year (bubble size ∝ track count).  
- **Duration & Loudness Trends**: Year-by-year line charts.

---

## Data Source & Preparation

- **Source**: Spotify Web API — track metadata and audio features for songs released 1980–2020.  
- **Extraction**: Custom Python script to query Spotify by decade slices.  
- **Transformation**:  
  - Filter out instrumentals and live recordings  
  - Normalize feature scales (e.g. energy, loudness)  
  - Compute aggregated metrics by year/artist  
- **Load**: Data model imported into Power BI Desktop (.pbix).

---

## How to Use

In this case the project is presented only on the pdf

---



