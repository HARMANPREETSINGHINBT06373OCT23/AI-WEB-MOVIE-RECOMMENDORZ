# AI-WEB-MOVIE-RECOMMENDORZ🎬 Movie Recommendation System
This is a learning project built using Streamlit, designed to recommend movies similar to a selected title based on cosine similarity. It also fetches movie posters using the TMDB API.


📂 Kaggle Dataset

🚀 Features
Recommend top 10 similar movies based on cosine similarity

Fetch and display posters using TMDB API

Simple interactive UI with Streamlit

⚠️ Note on Deployment
Due to GitHub and Streamlit limitations (file size limit of 100MB), the movie_data.pkl file could not be uploaded to the GitHub repo or deployed live.
You can download it manually from this Hugging Face link and place it in the project directory.

🧠 How It Works
Movie vectors are compared using cosine similarity

Recommendations are generated from a precomputed similarity matrix

Posters are fetched via TMDB API for a visual experience

🛠 Installation
Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/movie-recommendation-system.git
cd movie-recommendation-system
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Run the app:

bash
Copy
Edit
streamlit run app.py
 


<img width="1366" height="768" alt="Screenshot (159)" src="https://github.com/user-attachments/assets/7db62002-2c09-49db-bdec-012f221fa990" />

https://github.com/user-attachments/assets/4f312b69-b04e-4897-8d2e-ff9da31fa1bf


🙏 Credits
Dataset: TMDB Movie Metadata on Kaggle  https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata

Poster API: TMDB API
