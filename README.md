📚 Book Recommendation System

A Machine Learning based Book Recommendation System that suggests books using Popularity-Based Filtering and Collaborative Filtering.
The system recommends books to users based on ratings and similarity between books using Cosine Similarity.

---

🚀 Project Overview

This project builds a recommendation system that suggests books in two ways:

1. Top 50 Popular Books
   
   - Displays the most popular books based on number of ratings and average rating.

2. Book Recommendation System
   
   - Users can type the name of a book they like.
   - The system recommends 5 similar books based on user rating patterns.

---

🧠 Recommendation Techniques Used

1. Popularity-Based Recommendation

Books are ranked using:

- Number of ratings
- Average rating

This helps identify the Top 50 most popular books.

2. Collaborative Filtering

Collaborative filtering recommends books based on user behavior and rating patterns.

Steps involved:

- Create a User-Book rating matrix
- Analyze similarities between books
- Recommend similar books

3. Cosine Similarity

Cosine Similarity is used to measure similarity between books based on user ratings.

---

⚙️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook

---

📊 Dataset

The dataset contains:

- Book titles
- User ratings
- Book information

This dataset is used to train the recommendation models.

---

💡 Features

- Displays Top 50 Popular Books
- Book search functionality
- Recommends 5 similar books
- Uses collaborative filtering for better recommendations

---

📁 Project Workflow

1. Data Collection
2. Data Preprocessing
3. Popularity-Based Recommendation System
4. Collaborative Filtering Model
5. Similarity Calculation using Cosine Similarity
6. Book Recommendation Generation

---

📂 Project Structure

book-recommendation-system
│
├── dataset/                # Dataset files
├── notebooks/              # Jupyter notebooks
├── app.py                  # Application file (if used)
├── model.pkl               # Saved recommendation model
├── similarity.pkl          # Cosine similarity matrix
├── requirements.txt        # Dependencies
└── README.md               # Project documentation

---

▶️ How to Run the Project

1. Clone the repository

git clone https://github.com/your-username/book-recommendation-system.git

2. Navigate to the project directory

cd book-recommendation-system

3. Install required libraries

pip install -r requirements.txt

4. Run the project notebook or application

---

📸 Example Recommendation

Input Book:
Harry Potter and the Sorcerer's Stone

Recommended Books:

1. Harry Potter and the Chamber of Secrets
2. Harry Potter and the Prisoner of Azkaban
3. The Hobbit
4. The Golden Compass
5. Percy Jackson & the Olympians

---

📌 Future Improvements

- Add a web interface using Streamlit or Flask
- Improve recommendation accuracy
- Deploy the model online
- Add user login and personalization

---

👨‍💻 Author

Your Name

GitHub: https://github.com/shailjajigupta


---

⭐ If you like this project, consider giving it a stars
