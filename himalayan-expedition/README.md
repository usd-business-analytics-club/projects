# Himalayan Expeditions Analytics Challenge

This project invites you to explore over a century of Himalayan mountaineering records to uncover the human stories, strategic evolutions, and environmental challenges behind high-altitude expeditions. The goal is to use analytics and visualization to tell compelling, data-driven narratives from one of the world’s most dangerous frontiers.

## Challenge Overview

You are stepping into the shoes of a data analyst, historian, or digital storyteller. Your mission: to analyze this extensive dataset of mountaineering expeditions and bring insights to life through charts, maps, dashboards, or written storytelling. Whether you want to track peak popularity, model summit success probabilities, or visualize changes in seasonal strategies — the direction is up to you.

This challenge is deliberately **open-ended**, allowing for creativity across:

- Data journalism
- Exploratory data analysis (EDA)
- Risk profiling and historical trends
- Geospatial storytelling
- Dashboard design

## About the Dataset

The dataset is derived from the archives of **Elizabeth Hawley**, the renowned chronicler of Himalayan expeditions. It spans from **1905 to 2024**, and includes:

- **3 linked tables**: `exped.csv`, `peaks.csv`, and `refer.csv`
- **11,000+ expeditions**
- **480 documented peaks**

A detailed **data dictionary** is provided to help navigate variables across expeditions, peaks, and reference tables.

### Tables Summary

| File         | Description                                             |
|--------------|---------------------------------------------------------|
| `peaks.csv`  | Contains metadata about each mountain peak              |
| `exped.csv`  | Records expedition-level data such as dates, seasons, and outcomes |
| `refer.csv`  | Reference data (e.g., citizenships, organizations)      |

## Sample Research Questions

Here are a few open-ended directions to explore:

- What peaks are most attempted, and how do they differ in success/fatality rates?
- How have climbing seasons shifted over time?
- Can we trace notable historical years for Himalayan mountaineering?
- What role do specific countries or organizations play in organizing expeditions?
- Are certain peak locations more prone to failures or natural disasters?

## Tools & Technologies

- **Python**: `pandas`, `matplotlib`, `plotly`, `geopandas`
- **R**: `tidyverse`, `ggplot2`, `leaflet`
- **Tableau / Power BI**: For dashboards and storytelling visuals
- **Jupyter / R Markdown**: For reporting and narratives

## Project Folder Structure

```
himalayan-expeditions/
│
├── dataset/                    # Raw data files + data dictionary
│   ├── exped.csv
│   ├── peaks.csv
│   ├── refer.csv
│   └── himalayan_data_dictionary.csv
│
├── notebooks/                  # Analysis and visualization notebooks
│   ├── 01_expedition_eda.ipynb
│   ├── 02_peak_trends.ipynb
│   └── 03_geospatial_mapping.ipynb
│
├── outputs/                    # Final charts, visuals, dashboards
│
├── writeups/                   # Medium drafts, reports, blogs
│
└── README.md                   # Challenge overview and instructions
```

## Getting Started

1. **Review the data dictionary** (`himalayan_data_dictionary.csv`)
2. Load the CSV files and understand table relationships
3. Choose a focus: peak trends, expedition outcomes, or geographic storytelling
4. Use notebooks to develop visual and analytical narratives
5. Package your work into a dashboard, blog post, or visual story
