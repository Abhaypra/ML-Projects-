**Movie Recommendation System 🎬**
This is a content-based movie recommendation system built using Python and deployed with Streamlit for an interactive user experience.

**🔍 Goal**
Recommend movies based on the content similarity (tags, genres, overview) using natural language processing techniques.

**🧠 Tech Stack**
Python

Pandas, Scikit-learn

NLP (Bag of Words)

Cosine Similarity

Streamlit (App Deployment)

Pickle (Model Serialization)

**⚙️ How It Works**
Preprocessed movie metadata (overview + genre) to form a textual corpus.

Converted text into vectors using Bag of Words (BoW).

Calculated similarity between movies using cosine similarity.

Displayed top 5 similar movies for any selected title via a simple UI in Streamlit.

**📦 Usage**
Run the app locally using:

streamlit run app.py
**💡 Features**
Real-time movie recommendations

Lightweight and responsive Streamlit interface

Easy to modify and expand with more features


