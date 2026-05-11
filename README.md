🎬 Movie Recommendation System

A content-based Movie Recommendation System built using Machine Learning and a dataset of 45,000+ movies.
The system recommends similar movies based on metadata such as genres, keywords, cast, crew, and movie descriptions.

🚀 Features
🔍 Search movies instantly
🎯 Get top similar movie recommendations
📚 Trained on a dataset of 45k+ movies
🧠 Content-based recommendation engine
⚡ Fast recommendation generation using similarity matrices
💾 Exported model using Pickle
🌐 Frontend deployed with Streamlit
⚙️ Backend/API powered using FastAPI
🛠️ Tech Stack
Python
Pandas
NumPy
Scikit-learn
NLTK
Streamlit
FastAPI
Pickle
📂 Dataset

The project uses a movie metadata dataset containing over 45,000 movies including:

Movie titles
Genres
Cast
Crew
Keywords
Overview/description

Dataset preprocessing included:

Handling missing values
Feature extraction
Text vectorization
Data cleaning
Similarity computation
🧠 How It Works

The recommendation system follows a content-based filtering approach.

Workflow:
Combine important movie metadata
Convert text data into vectors using NLP techniques
Compute cosine similarity between movies
Recommend movies with the highest similarity scores
📸 Preview
Search your favorite movie
Get similar movie recommendations instantly
Interactive and simple UI
📁 Project Structure
Movie-Recommendation-System/
│
├── app.py                  # Streamlit frontend
├── main.py                 # FastAPI backend
├── movie_list.pkl          # Exported movie list
├── similarity.pkl          # Similarity matrix
├── notebook.ipynb          # Model training notebook
├── requirements.txt
└── README.md
⚙️ Installation

Clone the repository:

git clone https://github.com/your-username/Movie-Recommendation-System.git
cd Movie-Recommendation-System

Install dependencies:

pip install -r requirements.txt

Run Streamlit app:

streamlit run app.py

Run FastAPI server:

uvicorn main:app --reload
🌐 Live Demo

Frontend:
movie-recommend-jaskirat.streamlit.app

📌 Future Improvements
Add collaborative filtering
Integrate TMDB API for posters/details
User authentication
Personalized recommendations
Watchlist feature
Recommendation based on mood/genre
🤝 Contributing

Contributions are welcome!
Feel free to fork the repository and submit a pull request.
