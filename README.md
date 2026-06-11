# 🎬 Movie Recommendation System

## Project Overview

This is a Movie Recommendation System built using Python, Machine Learning, and Streamlit. The system recommends movies similar to a selected movie using Content-Based Filtering and Cosine Similarity.

The project analyzes movie features such as genres, keywords, cast, crew, and overview to generate personalized movie recommendations.

---

##  Features

- Movie recommendation based on similarity
- Content-Based Filtering
- Cosine Similarity Algorithm
- Interactive Streamlit Web Application
- Fast and user-friendly interface
- Machine Learning based recommendation engine

---

##  Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- Streamlit
- Pickle

---

## 📂 Dataset

The dataset used in this project is the TMDB 5000 Movies Dataset:
- tmdb_5000_movies.csv
- tmdb_5000_credits.csv

Due to GitHub file size limitations, the dataset files are not included in this repository.

Dataset source:
https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata

---

## Note

The `similarity.pkl` file is not included in this repository because it exceeds GitHub's file size limit.

To generate it, run the Jupyter Notebook provided in the `notebooks` folder. The notebook will preprocess the dataset, compute cosine similarity, and create the required pickle files.

---

##  Project Workflow

1. Data Collection
2. Data Preprocessing
3. Feature Engineering
4. Text Vectorization using CountVectorizer
5. Similarity Calculation using Cosine Similarity
6. Recommendation Generation
7. Streamlit Web Application

---

##  Project Structure

```text
Movie-Recommendation-System/
│
├── app.py
├── requirements.txt
├── README.md
├── .gitignore
│
└── notebooks/
    └── Movie_Recommendation_Model.ipynb
│
├── movies_dict.pkl
```

---

## ▶️ Installation

### Clone the Repository

```bash
git clone https://github.com/NandiniAgnihotri52/Movie-Recommendation-System.git
```

### Move to Project Directory

```bash
cd Movie-Recommendation-System
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Application

```bash
streamlit run app.py
```

---

##  Machine Learning Concept Used

The project uses Content-Based Recommendation.

Movies are recommended based on similarity between:

- Genres
- Cast
- Crew
- Keywords
- Movie Overview

Cosine Similarity is used to measure the similarity between movie vectors.

---

##  Future Enhancements

- Add movie posters
- Add movie ratings
- Add release year
- Netflix-style user interface
- Hybrid recommendation system

---

## 👨‍💻 Author

Nandini Agnihotri

B.Tech CSE (Data Science & AI)

Movie Recommendation System Project
