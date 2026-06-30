# 🎬 Movie Recommendation System

A content-based Movie Recommendation System built using **Python**, **Pandas**, **NumPy**, and **Scikit-learn**. The system recommends movies similar to the user's selected movie by analyzing movie metadata such as genres, keywords, cast, and crew.

---

## 🚀 Features

- Recommend similar movies instantly
- Content-based filtering
- Uses cosine similarity
- Preprocessed TMDB movie dataset
- Fast recommendations using precomputed similarity matrix
- Simple and easy-to-understand implementation

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook

---

## 📂 Dataset

This project uses the TMDB 5000 Movie Dataset.

Files included:

- `tmdb_5000_movies.csv`
- `tmdb_5000_credits.csv`

---

## 📁 Project Structure

```
Movie-recommendation-system/
│
├── Movie_recommendar_system.ipynb
├── tmdb_5000_movies.csv
├── tmdb_5000_credits.csv
├── movies.pkl
├── movie_dict.pkl
├── similarity.pkl
├── README.md
└── .gitignore
```

---

## ⚙️ Installation

### Clone the repository

```bash
git clone https://github.com/Aditya-12-k/Movie-recommendation-system.git
```

### Navigate to the project

```bash
cd Movie-recommendation-system
```

### Install required libraries

```bash
pip install pandas numpy scikit-learn nltk
```

---

## ▶️ Run the Project

Open the Jupyter Notebook:

```bash
jupyter notebook
```

Then open:

```
Movie_recommendar_system.ipynb
```

Run all cells to generate movie recommendations.

---

## 📌 How It Works

1. Load the TMDB movie and credits datasets.
2. Merge both datasets.
3. Clean and preprocess the data.
4. Extract important features like genres, cast, crew, keywords, and overview.
5. Convert text into vectors using CountVectorizer.
6. Calculate cosine similarity between movies.
7. Recommend the top similar movies based on user input.

---

## 📦 Requirements

- Python 3.10+
- Pandas
- NumPy
- Scikit-learn
- NLTK
- Jupyter Notebook

Install all dependencies:

```bash
pip install -r requirements.txt
```

---

## 🔮 Future Improvements

- Build a Streamlit web application
- Add movie posters using the TMDB API
- Add search suggestions
- Improve recommendation accuracy
- Deploy on Streamlit Cloud or Render



