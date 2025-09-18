# PopcornAI
🎬 CineMatch - Movie Recommender System

An AI-powered Movie Recommender System that suggests movies based on user preferences using content-based filtering and cosine similarity.
Built with 🐍 Python, ⚡ Scikit-learn, 📊 Pandas, and 🎨 Streamlit.

✨ Features
🎥 Content-based movie recommendations
🖥️ Simple and interactive Streamlit web app
📂 Preprocessed dataset with EDA
💾 Model saved with Pickle for fast loading
🛠️ Tech Stack
🐍 Python
📊 Pandas / NumPy
⚡ Scikit-learn
🎨 Streamlit
💾 Pickle

📂 Project Structure
📁 data/ : Dataset
▶️ app.py : Streamlit app
📓 recommender.ipynb : Jupyter notebook (EDA + Model building)
📑 requirements.txt : Dependencies


2️⃣ Install required packages:
pip install -r requirements.txt

3️⃣ Run the Streamlit app:
streamlit run app.py

📊 Example Output
If you search for "Inception", the system recommends:
🍿 Interstellar
🍿 Shutter Island
🍿 The Prestige
🍿 The Matrix
🍿 Memento

🚀 Future Improvements
🤝 Add collaborative filtering (user-based + hybrid recommendations)
🎞️ Integrate with TMDB API for posters, ratings, and more movie details
☁️ Deploy the app on Streamlit Cloud / Hugging Face / Heroku
🤝 Contributing
Pull requests are welcome! For major changes, open an issue first to discuss what you’d like to improve.
