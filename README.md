# 🎬 Movie MatchMaker

A Content-Based Movie Recommendation System built using Python and Machine Learning. This project recommends movies similar to a user's favorite movie by analyzing movie metadata such as genres, keywords, cast, crew, and overview.

---

## 📌 Project Overview

Movie MatchMaker uses **Content-Based Filtering** to find similar movies based on their features rather than user ratings. It processes the TMDB 5000 Movies dataset, extracts important information, converts text into numerical vectors using **TF-IDF Vectorization**, and calculates similarity using **Cosine Similarity**.

---

## 🚀 Features

- Recommend top 5 similar movies
- Content-based recommendation system
- Uses TF-IDF Vectorizer
- Calculates similarity using Cosine Similarity
- Saves processed data using Pickle
- Simple and beginner-friendly implementation

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Pickle
- Jupyter Notebook

---

## 📂 Dataset

This project uses the **TMDB 5000 Movie Dataset**.

Files used:
- `tmdb_5000_movies.csv`
- `tmdb_5000_credits.csv`

Dataset Source:
https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata

---

## 📁 Project Structure

```
Movie-MatchMaker/
│
├── matchmaker.ipynb
├── tmdb_5000_movies.csv
├── tmdb_5000_credits.csv
├── movies.pkl
├── similarity.pkl
├── README.md
└── requirements.txt
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Movie-MatchMaker.git
```

Move into the project folder:

```bash
cd Movie-MatchMaker
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ How It Works

1. Load movie and credits datasets.
2. Merge both datasets.
3. Select useful movie features.
4. Clean and preprocess text data.
5. Convert text into numerical vectors using TF-IDF.
6. Compute cosine similarity between movies.
7. Recommend the top 5 most similar movies.

---

## 💻 Example

```python
recommend("Avatar")
```

Example Output:

```
Guardians of the Galaxy
John Carter
Star Trek
Aliens
Star Wars
```

*(Recommendations may vary depending on preprocessing.)*

---

## 📚 Machine Learning Concepts Used

- Data Cleaning
- Feature Engineering
- Natural Language Processing (NLP)
- TF-IDF Vectorization
- Cosine Similarity
- Content-Based Recommendation System

---

## 📦 Dependencies

```
numpy
pandas
matplotlib
scikit-learn
```

Install manually:

```bash
pip install numpy pandas matplotlib scikit-learn
```

---

## 🎯 Future Improvements

- Build a Streamlit web application
- Add movie posters using the TMDB API
- Improve recommendations with hybrid filtering
- Add search autocomplete
- Deploy the project online

---

## 🤝 Contributing

Contributions, suggestions, and improvements are welcome.

1. Fork the repository
2. Create a new branch
3. Commit your changes
4. Open a Pull Request

---

## 📄 License

This project is intended for learning and educational purposes.

---

## 👨‍💻 Author

**Arman Kaur**

If you found this project helpful, consider giving it a ⭐ on GitHub!
