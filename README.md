# vrc-world-analyzer
# VRChat World Discovery & Recommendation Engine

**Status:** Actively in development

An end-to-end data-driven application that ingests public VRChat world metadata, stores and analyzes engagement signals, and recommends worlds to users based on similarity, popularity, and user preferences.

This project focuses on building a scalable data pipeline and recommendation system rather than scraping or automation.

---

## Features (Planned / In Progress)
- Ingest public VRChat world metadata via the VRChat API
- Store world data in a persistent database (SQLite)
- Engineer engagement and content-based features (tags, popularity, recency)
- Recommend worlds using similarity-based and ranking models
- Interactive dashboard for browsing and discovering worlds

---

## Tech Stack
**Backend / Data**
- Python
- Requests
- SQLite
- Pandas

**Machine Learning**
- Scikit-learn (content-based recommendations)
- Text feature extraction (TF-IDF / embeddings)

**Frontend**
- Streamlit
- Plotly

---

## Data Source
Publicly available VRChat world metadata accessed via the VRChat API in accordance with VRChat’s terms of service.

This project does not collect private user data or automate interactions on the platform.

---

## Project Goals
- Demonstrate API integration and data modeling
- Apply recommendation system fundamentals
- Build a user-facing data product end-to-end
- Follow ethical and responsible data usage practices

---

## Disclaimer
This project is for educational purposes only and is not affiliated with VRChat Inc.
