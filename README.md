
# 📺 Netflix Data Analysis Project

This project analyzes a dataset of Netflix movies and TV shows to uncover trends and patterns in content distribution.  
The goal is to understand how Netflix has evolved over time in terms of **genres, ratings, languages, and release trends**.

---

## 📌 Objectives
- Clean and preprocess the dataset
- Perform exploratory data analysis (EDA)
- Visualize trends in content distribution
- Derive insights on Netflix’s catalog growth and focus areas

---

## 📊 Dataset
The dataset (`mymoviedb.csv`) contains around **10,000 records** with columns such as:
- **Title** – Name of the movie/show
- **Genre** – Category of content
- **Release Date** – Year of release
- **Country** – Country of production
- **Rating** – Audience rating (e.g., PG, TV-MA)
- **Language** – Original language
- Other metadata fields

---

## 🛠️ Tools & Libraries Used
- **Python**
- **Pandas** (data cleaning & manipulation)
- **NumPy** (numerical operations)
- **Matplotlib & Seaborn** (visualization)
- **Jupyter Notebook**

---

## 🔎 Key Steps
1. Data Cleaning
   - Removed duplicates and missing values
   - Converted `Release_Date` into datetime and extracted year
   - Dropped irrelevant columns like `Overview`, `Poster_URL`

2. Exploratory Data Analysis
   - Distribution of content across years
   - Movies vs TV shows count
   - Most common ratings
   - Top genres and countries producing content

3. Visualization
   - Line plots, bar charts, and count plots
   - Clear titles and axis labels for better readability

---

## 📈 Insights & Conclusion
- Netflix significantly expanded its catalog **after 2015**
- **TV shows** have grown as a share of total content
- **TV-MA** is the most common rating, highlighting mature audience focus
- Content is primarily in **English**, but international content is rising
- **Drama** and **Comedy** are consistently the most popular genres

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/netflix-data-analysis.git
