# 🎬 WatchFlix – AI-Powered Movie Recommender 🍿

🔥 *Your next favorite movie is just one click away!*  
**WatchFlix** is a smart, NLP-powered movie recommendation system that delivers personalized suggestions based on cast, genres, keywords & production companies. Built with ❤️ using Python & Streamlit.

---

## 🎯 Problem Statement

In a world of content overload, users struggle to decide what to watch next. Most existing platforms either use black-box algorithms or provide generic suggestions. I wanted to solve this by building a transparent, content-based recommendation system that helps users discover movies similar to ones they already like — based on features they intuitively relate to, like genre, cast, or director.



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

## 🔄 Workflow

### 🔹 Data Ingestion & Merging:
- Used TMDB 5000 Movies + Credits datasets.
- Merged on title to combine metadata.

### 🔹 Preprocessing & Feature Engineering:
- Extracted relevant features: genres, keywords, cast, director, production company.
- Cleaned and normalized data: removed stopwords, stemmed words using `PorterStemmer`.
- Created a `tags` column by combining all descriptive metadata into a single text blob per movie.

### 🔹 Vectorization & Similarity:
- Used `CountVectorizer` to transform text into vectors.
- Computed Cosine Similarity matrices for:
  - Tags  
  - Genres  
  - Cast  
  - Production company  
  - Keywords  

### 🔹 Caching:
- Stored similarity matrices and processed data as `.pkl` files for improved performance.

### 🔹 Frontend UI (Streamlit):
- Movie Recommendations by 5 categories.
- Movie Detail Page with dynamic posters and cast biographies.
- All Movies Browser with pagination and posters.

---

## 📈 Impact

✅ Helped users discover relevant movies across different criteria — *“like this because of cast”* or *“same genre”*.  
✅ Delivered sub-second performance using cached data and efficient similarity search.  
✅ Designed with scalability and modularity — clean separation between preprocessing, caching, and UI logic.  
✅ Mimicked a real product experience: end-to-end from raw data → ML logic → UI → dynamic API integration.


---

## 🚀 Launch the App

🔗 [Click here to try WatchFlix](https://watchflix.streamlit.app/)  

---

## 📸 Sneak Peek

### 🔥 Movie Recommendations View
![Recommendations](https://github.com/PANWAR-MAYANK/WatchFlix/blob/master/Images/Recommender.PNG)

### 🎬 Movie Description Page
![Movie Description](https://github.com/PANWAR-MAYANK/WatchFlix/blob/master/Images/Description.PNG)

### 📚 All Movies Browser
![All Movies](https://github.com/PANWAR-MAYANK/WatchFlix/blob/master/Images/Browse.PNG)


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


