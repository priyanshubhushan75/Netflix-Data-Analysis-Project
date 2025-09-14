# 📊 Netflix Data Analysis & Insights  

## 📌 Project Overview  
This project analyzes the **Netflix dataset** to explore content trends, top actors, genres, release patterns, and more.  
Along with **EDA (Exploratory Data Analysis)**, the project also applies **Machine Learning techniques** such as classification, clustering, sentiment analysis, and recommendation systems.  

The goal is to **uncover insights about Netflix’s content library** and practice **data visualization + ML concepts**.  

---

## ⚙️ Tech Stack  
- **Python** (Pandas, NumPy)  
- **Visualization**: Matplotlib, Seaborn  
- **Machine Learning**: Scikit-learn, Statsmodels  
- **NLP**: TextBlob  
- **Jupyter Notebook**  

---

## 🔍 Exploratory Data Analysis (EDA)  

### 📈 Visualizations
- **Top 10 Genres** – Bar chart of most common genres.  
- **Top 5 Directors / Actors** – Horizontal bar chart of most featured people.  
- **Content by Year** – Line plot showing growth of Netflix content over time (post-2010).  
- **Movies vs TV Shows** – Comparison of releases per year.  
- **USA-specific Trends** – Movies vs TV shows released in the USA after 2010.  
- **Average Duration** – Movies (in minutes) vs TV Shows (in seasons).  
- **Pie Chart of Genres** – Distribution of top genres.  
- **Dashboards** – Multi-chart dashboards with 6 plots (top countries, actors, years, ratings, longest movies, genres).  

---

## 🤖 Machine Learning Experiments  

### 1️⃣ **Recommendation System**  
- Built a **content-based filtering recommender** using TF-IDF + Cosine Similarity.  
- Suggests similar titles based on cast, director, and genre.  

### 2️⃣ **Classification (Movie vs TV Show)**  
- Features: Duration, Genre.  
- Model: Random Forest Classifier.  
- Achieved high accuracy in predicting type.  

### 3️⃣ **Time Series Forecasting**  
- Used ARIMA model on **release_year trends**.  
- Forecasts number of titles Netflix may release in the next 5 years.  

### 4️⃣ **Clustering Genres**  
- Applied **K-Means** on genre text features.  
- Grouped genres into 5 clusters for content categorization.  

### 5️⃣ **Sentiment Analysis (Descriptions)**  
- Analyzed `description` column using TextBlob.  
- Sentiment polarity distribution shows overall positive/neutral tone.  

---

## 📂 Project Structure  
```
Netflix-Analysis/
│-- data/                 # Netflix dataset (csv)
│-- notebooks/            # Jupyter Notebooks with analysis
│-- images/               # Saved plots
│-- README.md             # Project Documentation
│-- requirements.txt      # Required Python libraries
```

---

## 🚀 How to Run  

1. Clone the repo:  
   ```bash
   git clone https://github.com/yourusername/netflix-analysis.git
   cd netflix-analysis
   ```
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```
3. Run Jupyter Notebook:  
   ```bash
   jupyter notebook
   ```
4. Open `netflix_analysis.ipynb` and run cells.  

---

## 📌 Future Improvements  
- Add **deep learning recommendation system**.  
- Deploy dashboards with **Streamlit / Power BI**.  
- Expand dataset with IMDb ratings for richer insights.  

---

## 🏆 Key Learnings  
- Data cleaning & preprocessing in Pandas.  
- Multi-plot dashboards with Matplotlib.  
- Applying ML concepts (Classification, Clustering, Forecasting).  
- Building a simple **Recommender System**.  
- NLP sentiment analysis.  
