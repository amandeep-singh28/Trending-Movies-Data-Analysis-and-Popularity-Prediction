# 🌌🎬 Trending-Movies-Data-Analysis-and-Popularity-Prediction


An interactive and aesthetic movie analytics dashboard built using **Python, MySQL, and Power BI**, integrated with a **Decision Tree Classification Model** to predict movie popularity. Designed with a **moonlit purple-pink landscape theme** to deliver insights with clarity and creativity.

---

## 🧩 **1. Project Workflow Overview**

This project follows a structured **ETL pipeline**:

- **Python (Pandas)**: Data cleaning, preprocessing, and creation of dimension & fact tables.
- **MySQL Workbench**: Imported cleaned tables to validate relational structures.
- **Power BI**: Designed a visually appealing dashboard matching the **moonlit background wallpaper** for professional presentation.

---

## 🧹 **2. Data Cleaning & Preparation (Python)**

✅ **Datasets Used:**
- `titles.csv` (Movies & Shows metadata)
- `credits.csv` (Cast & Crew data)

### 🔧 **Cleaning Steps**
- Removed duplicates and missing rows.
- Created **Revenue column (in millions)** directly in the **Facts table**.
- Split into **four relational tables**:

| 🗃 **Table Name** | 🔍 **Description** |
|-----------------|---------------------|
| **Facts Table** | ID, Runtime, IMDb Score, IMDb Votes, TMDb Popularity, TMDb Score, Revenue |
| **Titles Table** | ID, Title, Type, Description, Release Year |
| **Genre Table** | ID, Genre (each genre per movie in rows) |
| **Character Table** | ID, Name, Role from credits dataset |

✅ Structured with **primary and foreign keys** for clean Power BI data modeling.

---

## 💾 **3. SQL Database & Testing**

- Imported all tables into **MySQL Workbench** to test schemas and relationships.
- ✅ **No advanced queries executed yet** – future scope includes deriving business insights via SQL analytics.

---

## 📊 4. Data Visualization (Python)

In addition to Power BI visualizations, exploratory data analysis was performed using **Python (Matplotlib & Seaborn)** to derive initial insights:

1. **Distribution of IMDb Scores** – Histogram + KDE to see score spread.
2. **Runtime vs IMDb Score based on Type** – Scatter plot coloured by Type (Movie/Show).
3. **Movie Counts by Type** – Count plot to compare the number of Movies vs Shows.
4. **IMDb Score by Age Certification** – Box plot to visualise ratings across certifications.

These plots provided a clear understanding of data characteristics before modelling and dashboarding.

---

## 📊 **5. Power BI Dashboard**

### 🎨 **Theme**
- **Background:** Moonlit purple-pink landscape with silhouetted hills and starry sky.
- **Design Principle:** Clean dark mode layout with minimalist white KPI cards and vibrant bar charts for contrast.

### 🔷 **Dashboard Elements**

✅ **KPI Cards**
- Total Movies
- Average IMDb Score
- Total Revenue (Millions)
- Average Runtime (Mins)

✅ **Visuals Created**
- **Bar Chart:** Top 10 movies by IMDb Score
- **Funnel Chart:** Top 5 characters by movie count
- **Line Chart:** Movie releases over years
- **Matrix Table:** Genre-wise movie count

✅ **Filters & Slicers**
- Release Year
- Genre

✅ **Buttons**
- **Reset to Default:** Clears all filters to dashboard defaults.

---

## 🧠 **6. Machine Learning Implementation**

### 🔷 **Model Used:** Decision Tree Classifier

- **Objective:** Predict **‘High’ or ‘Low’ popularity categories** for movies based on features.
- **Algorithm:** `DecisionTreeClassifier` from sklearn.
- **Performance:** ~78% accuracy.
- **Outcome:** Generated interpretable splits showcasing how movie popularity is classified using numerical features.

---

## 📁 **Dataset Used**

The data for this project was sourced from [Kaggle – Netflix TV Shows and Movies Dataset](https://www.kaggle.com/datasets/victorsoeiro/netflix-tv-shows-and-movies).

### 📌 **Dataset Details**

- Includes metadata of Netflix shows and movies such as:
  - **Title**
  - **Genre**
  - **Cast**
  - **Release Year**
  - **Runtime**
  - **Production Countries**
  - **IMDb & TMDb Ratings**
  - **Popularity**
  - and more.

- **Primary CSV Files Used:**
  - `titles.csv` – contains movie/show metadata.
  - `credits.csv` – contains actor/character details.

---

### 🔗 **Access the Dataset**

[![Kaggle Dataset](https://img.shields.io/badge/View%20on-Kaggle-blue)](https://www.kaggle.com/datasets/victorsoeiro/netflix-tv-shows-and-movies)

> 📎 **Link:** [https://www.kaggle.com/datasets/victorsoeiro/netflix-tv-shows-and-movies](https://www.kaggle.com/datasets/victorsoeiro/netflix-tv-shows-and-movies)

---

## 📌 **7. Final Thoughts & Future Scope**

✅ **Theme Integration:** Harmonised visuals with the moonlit wallpaper background.  
✅ **Dynamic Dashboard:** Fully interactive with genre and release year filters.  
✅ **ML Integration:** Demonstrated classification model for predictive analytics.  
✅ **Next Steps:**
- Execute meaningful **SQL queries** for business insights.
- Develop a **dedicated ML deployment project** linking decision tree outputs to Power BI for real-time classifications.

---

> 🙌 **Built with dedication, creativity, and data science discipline to analyse movies and predict popularity under a calming moonlit theme.**

---

### 🔗 **Connect**

Feel free to connect for collaboration, reviews, or suggestions to enhance this project further.



