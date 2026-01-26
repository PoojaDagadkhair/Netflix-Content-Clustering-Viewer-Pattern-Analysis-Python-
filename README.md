# Netflix-Content-Clustering-Viewer-Pattern-Analysis(Python) 


## 📌 Project Overview
This project performs an in-depth analysis of Netflix movies and TV shows from **2005 onwards** to uncover content trends, regional popularity, and Netflix’s content strategy. By integrating external datasets such as **IMDb ratings** and **Rotten Tomatoes**, the project explores audience preferences and builds a **content-based recommendation system** using clustering techniques.

---

## 🎯 Objectives
The project was designed with three key goals:
1. Analyze Netflix’s content composition and growth trends.
2. Understand the popularity of movies and TV shows across different countries and Netflix’s content preferences.
3. Group similar movies and TV shows to support a recommendation system.

---

## 📂 Dataset
- **Source:** Flixable (Netflix search engine)
- **Records:** 7,787
- **Attributes:** 11  
- **Additional Data:** IMDb ratings, Rotten Tomatoes scores

---

## 🛠️ Tools & Technologies
- **Python**
- **Pandas & NumPy** – Data manipulation
- **Matplotlib & Seaborn** – Data visualization
- **Scikit-learn** – Machine learning & clustering
- **TF-IDF Vectorization** – Text feature extraction
- **PCA (Principal Component Analysis)** – Dimensionality reduction

---

## 🔄 Project Workflow

### 1️⃣ Data Collection & Cleaning
- Collected Netflix data from Flixable.
- Cleaned missing values and standardized categorical features.
- Performed exploratory data analysis to identify trends.

### 2️⃣ Exploratory Data Analysis (EDA)
- Observed a steady increase in **TV shows** and a decline in **Movies after 2010**, especially in the US.
- Identified country-wise and genre-wise content distribution.

### 3️⃣ Feature Engineering
- Selected key features such as:
  - Cast
  - Country
  - Genre
  - Director
  - Rating
  - Description
- Converted text data using **TF-IDF vectorization**.
- Applied **PCA** to reduce dimensionality and improve clustering performance.

### 4️⃣ Clustering & Recommendation System
- Applied **K-Means** and **Agglomerative Clustering**.
- Grouped similar content into clusters.
- Built a basic **content-based recommendation system** based on cluster similarity.

---

## 📈 Key Insights
- TV shows are becoming more popular than movies on Netflix.
- Most searched content includes themes like:
  - Love & Relationships
  - Personal Growth & Discovery
  - Social & Emotional Connections
- **International Movies, Dramas, and Comedies** are the most popular genres.
- Least popular genres include:
  - Classic & Cult TV
  - TV Thrillers
  - Stand-Up Comedy
  - Talk Shows
- Majority of Netflix content still originates from the **United States**.

---

## ✅ Conclusion
This project demonstrates how **text analysis and clustering techniques** can reveal hidden patterns in streaming content. The recommendation system highlights how data-driven methods can enhance personalized content suggestions and support strategic decision-making.

---

## 🚀 Future Improvements
- Integrate user watch history for collaborative filtering.
- Optimize the recommendation engine with hybrid models.
- Deploy the recommendation system as a web application.

---

## 👩‍💻 Author
**Pooja Dagadkhair**  
Data Analytics & Power BI Enthusiast  

🔗 GitHub: https://github.com/PoojaDagadkhair  
🔗 LinkedIn: https://www.linkedin.com/in/poojadkhair  

---

⭐ If you found this project useful, feel free to star the repository!
