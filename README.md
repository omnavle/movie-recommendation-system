# 🎬 Movie Recommendation System

A production-ready, full-stack AI-powered Movie Recommendation System
built using Machine Learning, FastAPI, and Streamlit.

This project demonstrates end-to-end system design --- from model
building to API development to UI deployment.

------------------------------------------------------------------------

## 🚀 Live Architecture

User\
⬇\
Streamlit Frontend\
⬇\
FastAPI Backend\
⬇\
TF-IDF Model + TMDB API

------------------------------------------------------------------------

## 🧠 Core Concept

This system uses **Content-Based Filtering** powered by:

-   TF-IDF Vectorization
-   Cosine Similarity
-   Genre-based recommendation logic
-   TMDB API integration for posters & metadata

### Similarity Formula

Similarity = (A · B) / (\|\|A\|\| × \|\|B\|\|)

Movies are recommended based on textual similarity of descriptions.

------------------------------------------------------------------------

## ✨ Key Features

-   🔍 Smart movie search with suggestions\
-   🎯 AI-based TF-IDF recommendations\
-   🎭 Genre-based recommendations\
-   🎥 Live movie posters & metadata (TMDB API)\
-   🏠 Trending / Popular home feed\
-   💎 Modern Netflix-style UI\
-   ⚡ FastAPI high-performance backend\
-   🌐 Production deployment ready

------------------------------------------------------------------------

## ⚙️ Installation Guide

## ⚙️ Installation Guide

### 1️⃣ Clone Repository

```bash
git clone https://github.com/omnavle/movie-recommendation-system.git
cd movie-recommendation-system
```

### 2️⃣ Create Virtual Environment

```bash
python -m venv .venv\
.venv`\Scripts`{=tex}`\activate  `{=tex}
```

### 3️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 4️⃣ Configure Environment Variables

Create a `.env` file in the root directory:
```bash
TMDB_API_KEY=your_tmdb_api_key_here
```
Get your API key from:\
https://www.themoviedb.org/settings/api

------------------------------------------------------------------------

## ▶️ Run Application

### Start Backend
```bash
uvicorn main:app --reload
```
Backend runs at:\
```bash
http://127.0.0.1:8000
```
### Start Frontend
```bash
streamlit run app.py
```
------------------------------------------------------------------------

## 📡 API Endpoints

-   /home -- Trending / Popular movies\
-   /tmdb/search -- Keyword search\
-   /movie/id/{id} -- Movie details\
-   /recommend/tfidf -- TF-IDF recommendations\
-   /recommend/genre -- Genre-based recommendations\
-   /movie/search -- Combined recommendation bundle\
-   /health -- Health check

------------------------------------------------------------------------

## 🛠 Tech Stack

Python • FastAPI • Streamlit • Scikit-learn • Pandas • NumPy • HTTPX •
TMDB API
