# 🎬 OTT Content Dashboard & Recommender

This project analyzes and recommends TV shows and movies from major OTT platforms — **Netflix**, **Amazon Prime**, **Hulu**, and **Disney+**. Using cleaned and merged datasets, it explores content trends across platforms through engaging visualizations like **pie charts**, **line charts**, **scatter plots**, and **treemaps**.

---

## 🤖 Recommendation System

A content-based recommender system is built using **TF-IDF Vectorizer** and **Cosine Similarity**. It includes:

- `recommend_show()` – Suggests similar **TV shows**
- `recommend_movies()` – Suggests similar **movies**
- `find_your_mind()` – An interactive, guided tool based on:
  - Content type (TV show / Movie)
  - Release period (Old / Recent)
  - Age group
  - Up to 3 genres
  - Optional platform filter

---

## 📊 Visualizations

The project includes multiple charts to understand content trends:

- 📊 **Bar chart** – Count of content per platform  
- 🥧 **Pie charts** – Genre and platform distribution  
- 📈 **Line charts** – Titles released per year  
- 🌐 **WordCloud** – Most frequent words in descriptions/genres 

---

## 🎯 Goals

To demonstrate practical skills in:

- Data cleaning and preprocessing
- Exploratory data analysis (EDA)
- Text-based machine learning
- Visual storytelling using real-world data
- Code modularity and readability

This project is structured for further deployment via **Streamlit** or **dashboard tools** like **Power BI**.

---

## 📂 Data Sources

- Kaggle: Netflix Titles Dataset  
- Kaggle: Prime, Hulu, Disney+ Dataset  
- Merged and standardized with added fields like `platform`, `type`, `duration`, and `genre`

---

## 🧠 Ideal For:

- Portfolio projects  
- Interview discussions  
- Data science learning  
- Recommender system practice  

---

Feel free to fork, improve, or integrate into your own dashboard!
