
# NMF-Based Movie Recommendation System

Hi, This is Parth Kohale, the one who made the project, I have been buidling and making deep learning related stuff for more than a year now but never took the efforts to actually post these projects so here goes probably something or nothing.. Enjjoyy your day, and if you have any suggestions please go ahead and let me know, i will be glad! Thank you, bye!

## Overview

Recommendation systems are widely used in streaming platforms and online entertainment services to provide personalized content suggestions to users. This project focuses on building a movie recommendation system using Non-Negative Matrix Factorization (NMF), a collaborative filtering technique commonly used in recommendation engines.

The objective of this project is to recommend movies to users based on learned latent patterns in movie features and user preferences. Using movie metadata and feature extraction techniques such as TF-IDF vectorization, the system identifies similarities between movies and generates personalized recommendations.

This project demonstrates:

* Recommendation system development
* Feature extraction using TF-IDF
* Dimensionality reduction with NMF
* Content-based filtering techniques
* Personalized movie recommendation generation

The dataset used in this project contains movie-related information from the TMDB dataset, including titles, genres, descriptions, and metadata used to build recommendation features.

By leveraging Non-Negative Matrix Factorization, the system learns hidden relationships between movies and generates recommendations based on content similarity and latent feature representations.

---

# Features

* Movie recommendation system using NMF
* TF-IDF feature extraction
* Content-based recommendation engine
* Similar movie discovery
* Personalized recommendation generation
* Latent feature learning using matrix factorization

---

# Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* SciPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

# Dataset Information

Dataset files included:
* Has been imported from kaggle using their kagglehub library.
* `TMDB_movie_dataset.csv`

The dataset contains:

* Movie titles
* Genres
* Descriptions
* Metadata and textual features

The TF-IDF matrix was generated from movie textual information and used as input for the recommendation model.

---

# Recommended Project Structure

```bash id="0shw9n"
nmf-movie-recommendation-system/
│
├── notebooks/
│   ├── Movie_Recommendation_System_using_NMF.ipynb
│   └── movie_recommendation_system_using_nmf.py
│
├── README.md
├── requirements.txt
└── LICENSE
```

---

# requirements.txt

```text id="hfob5j"
pandas
numpy
scikit-learn
scipy
matplotlib
seaborn
jupyter
ipykernel
```

---


# Model Architecture

The recommendation system follows this workflow:

1. Load movie metadata dataset
2. Perform text preprocessing
3. Generate TF-IDF feature vectors
4. Apply Non-Negative Matrix Factorization (NMF)
5. Learn latent movie feature representations
6. Compute movie similarities
7. Generate personalized movie recommendations

NMF helps reduce dimensionality while identifying hidden relationships between movie features.

---

# Results

The recommendation system successfully generated movie recommendations based on learned content similarities and latent patterns.

Key achievements:

* Built a content-based recommendation engine
* Applied matrix factorization techniques
* Generated relevant movie recommendations
* Improved recommendation efficiency using dimensionality reduction

---

# Installation

Clone the repository:

```bash id="jlwmwl"
git clone https://github.com/ParthKohale/movie-recommendation-system-nmf.git
```

Install dependencies:

```bash id="p7d4kp"
pip install -r requirements.txt
```

---

# Usage

Run the notebook:

```bash id="0lgqqs"
jupyter notebook
```

Open:

```bash id="9t3r5w"
notebooks/Movie_Recommendation_System_using_NMF.ipynb
```

Run all cells to generate movie recommendations.

---

# Future Improvements

* Add collaborative filtering techniques
* Integrate user ratings and reviews
* Build a web application using Flask or Streamlit
* Implement hybrid recommendation systems
* Add real-time recommendation support
* Improve scalability for large datasets

---

# Applications

This project can be extended for:

* Streaming platforms
* OTT recommendation systems
* Personalized content discovery
* Entertainment recommendation engines
* AI-powered movie suggestion systems

---


# License

This project is licensed under the MIT License.
