# 🎬 WatchFlix – AI-Powered Movie Recommender 🍿

🔥 *Your next favorite movie is just one click away!*  
**WatchFlix** is a smart, NLP-powered movie recommendation system that delivers personalized suggestions based on cast, genres, keywords & production companies. Built with ❤️ using Python & Streamlit.

---

## ✨ Project Features

- 🧠 **NLP-based Filtering**: Using cosine similarity on content features
- 📚 **Smart Recommendations**: Based on tags, genres, cast & production
- 🖼️ **Movie Posters & Details**: Clean and informative movie view
- 🧾 **Full Movie Explorer**: Browse all movies via an interactive slider
- 💾 **Speed Optimized**: Uses `pickle` to load preprocessed data quickly
- 🌍 **Streamlit Web App**: Seamless user experience with smooth navigation

---

## 🔧 Tech Stack at a Glance


| 💻 **Technology** | 🔧 **Tool/Library**                     |
|------------------|-----------------------------------------|
| Programming      | Python 🐍                                |
| Data Handling    | Pandas 📊, NumPy 🔢 , Serialization - `Pickle`                      |
| NLP              | CountVectorizer (Scikit-learn) 🧠, NLTK - `Bag of Words`, `Stopwords Removal`, `Text Vectorization`           |
| ML Similarity    | Cosine Similarity 🔁                     |
| UI/UX            | Streamlit - Poster Display, Search Interface, Responsive Layout                             |
| Data Storage     | CSV Files 📂, Pickle Serialization 🥒     |
| Deployment       | GitHub, Streamlit Cloud ☁️                       |
| Version Control  | Git & GitHub 🗂️                          |
| 📈 Optimization        | Efficient File Caching, Modular Code Structure                                       |


---

## 🚀 Launch the App

🔗 [Click here to try WatchFlix](https://watchflix.streamlit.app/)  

---

## 📸 Sneak Peek

| 🔥 Movie Page                            | 📚 All Movies View                        |
|-----------------------------------------|-------------------------------------------|
| ![Movie Info](https://github.com/PANWAR-MAYANK/WatchFlix/assets/96871662/cce0c494-4dde-4872-868b-2f6f23b24a68) | ![All Movies](https://github.com/PANWAR-MAYANK/WatchFlix/assets/96871662/02473070-91cf-45a0-8016-eee8b70ee2ae) |

---

## ⚙️ Local Setup in Minutes

# 1. Clone the Repo
```

git clone https://github.com/PANWAR-MAYANK/WatchFlix.git
cd WatchFlix
```


# 2. Optional: Set up a virtual environment
```

python -m venv venv
# Activate: venv\Scripts\activate (Windows) OR source venv/bin/activate (Linux/Mac)
```


# 3. Install required packages
```

pip install -r requirements.txt
```


# 4. Run the app
```

streamlit run main.py
```

--- 

## 🧠 How It Works

- 🧾 Load and preprocess data (movies, cast, crew, keywords)

- 🧬 Combine important columns into a unified "tag"

- ✨ Vectorize using CountVectorizer (BoW Model)

- 🔍 Use cosine similarity for recommendations

- 📥 Save vectorized data and similarities using Pickle

- 🎬 Show posters and movie info using TMDB image links

---

## 💼 Why This Project Matters

✅ Real-world data pipeline
✅ Deployment-ready application
✅ Full-stack ML project
✅ Efficient, scalable & user-centric
✅ Impressively clean UI & UX

---

## 📃 License

This project is open-source under the MIT License.

---

## 🙌 Let’s Connect!

📧 Drop me a message, I’d love to collaborate or talk!


