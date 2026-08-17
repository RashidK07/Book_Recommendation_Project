# 📚 Book Recommendation System



A machine-learning-based "Book Recommendation System" built using Python and Streamlit.

The application uses "collaborative filtering" to recommend books based on user-book rating patterns. It also provides a list of the "Top 50 popular books" from the catalog.



### 🌐 Live Demo

👉 [Open the Book Recommendation System](https://bookrecommendationproject-ff8xgpzkazmzhta7z9xa2r.streamlit.app/)

---

### 📸 Application Preview

### 🏠 Main Application

![Book Recommendation System](ScreenShots/Book_Recommend_1.png)

### 📚 Book Recommendations

![Book Recommendations](ScreenShots/Book_Recommend_2.png)

### 📊 Dataset Explorer

![Dataset Explorer](ScreenShots/Book_Recommend_3.png)

---

### ✨ Features


📚 Top 50 Books — Displays the 50 most popular books in the catalog.

🔍 Book Recommendation — Select a book and receive 5 similar book recommendations.

🖼️ Book Covers — Displays book cover images along with title and author.

📊 Dataset Explorer — Allows users to view the books, ratings, and users datasets.

🌐 Interactive Web Application — Built and deployed using Streamlit.

---

### 🧠 How the Recommendation System Works


The recommendation system uses "collaborative filtering".



The system analyzes user-book rating interactions to identify books that have similar rating patterns. When a user selects a book, the system finds books with the highest similarity scores and displays the top 5 recommendations.



The recommendation pipeline uses pre-computed data and similarity scores stored in `.pkl` files.

---

### 🛠️ Technologies Used



- Python

- Pandas

- NumPy

- Streamlit

- Pickle

- Jupyter Notebook

- Git & GitHub

- Git LFS

---

### 📂 Project Structure



Book_Recommendation_Project


├── Data/

│   ├── Books.csv

│   ├── Ratings.csv

│   └── Users.csv

│

├── ScreenShots/

│   └── Book_Recommend_1.png

│   └── Book_Recommend_2.png

│    └── Book_Recommend_3.png

│

├── app.py

├── books.pkl

├── popular.pkl

├── pt.pkl

├── similarity_scores.pkl

├── Recommender.ipynb

├── requirements.txt

├── HowToRunOnTerminal.txt

├── README.md

├── .gitignore

└── .gitattributes

