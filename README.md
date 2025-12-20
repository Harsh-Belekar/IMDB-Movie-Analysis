# 🎬 IMDB Movie Analysis

A **Data Science project** that analyzes IMDB movie ratings to uncover insights about rating distribution, top-rated movies, genre performance, and year-wise trends.  
The project combines **Python-based analysis** with an **Interactive Power BI dashboard** for effective data storytelling.

> 📌 **Task 2 – Data Science Internship at HexSoftwares**

---

## 📊 Project Objectives

Using the IMDB movie ratings dataset, this project aims to:

- Clean and preprocess raw movie data  
- Calculate summary statistics (mean, median, mode) of ratings  
- Visualize rating distribution using histogram and box plot  
- Identify top-rated movies and genres  
- Build a simple analytical dashboard using **Power BI**

---

## 🛠 Tools & Technologies

- **Python**
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
- **Jupyter Notebook**
- **Power BI** (Dashboard & Reporting)

---

## 📂 Project Structure

```
│
├── IMDB Movie Analysis Dashboard.pbix
├── IMDB Movie Analysis Dashboard.pdf
├── IMDB_Movie_Analysis.ipynb
├── IMDB_Movie_Data.csv
├── README.md
├── requirements.txt
└── images/
    ├── Box Plot of IMDB Ratings.png
    ├── Distribution of IMDB Ratings.png
    ├── IMDB Movie Analysis Report.png
    └── Top Rated Genres on IMDB.png
```

---

## 🧹 Data Cleaning & Preprocessing

- Handled missing values:
  - **Revenue (Millions)** → replaced using **median**
  - **Metascore** → replaced using **mean**
- Converted columns to appropriate data types
- Removed duplicates to ensure data consistency

---

## 📈 Exploratory Data Analysis

### 🔹 Distribution of IMDB Ratings
![Distribution of IMDB Ratings](images/Distribution%20of%20IMDB%20Ratings.png)

> Most movies are rated between **6 and 8**, indicating generally positive audience reception.

---

### 🔹 Box Plot of IMDB Ratings
![Box Plot of IMDB Ratings](images/Box%20Plot%20of%20IMDB%20Ratings.png)

> The box plot highlights rating spread and identifies outliers.

---

### 🔹 Top Rated Genres
![Top Rated Genres](images/Top%20Rated%20Genres%20on%20IMDB.png)

> Genres such as **Drama**, **Biography**, and **Adventure** tend to have higher average ratings.

---

## 📊 Power BI Dashboard

An **interactive Power BI dashboard** was created to present insights in a business-friendly format.

### 🔹 Dashboard Highlights
- KPI cards: Total Movies, Average Rating, Highest Rating
- Rating distribution chart
- Top-rated movies table
- Genre-wise average ratings
- Year-wise rating trend
- Interactive filters (Year, Genre, Rating)

![IMDB Power BI Dashboard](images/IMDB%20Movie%20Analysis%20Report.png)

📁 Files:
- `IMDB Movie Analysis Dashboard.pbix`
- `IMDB Movie Analysis Dashboard.pdf`

---

## 📌 Key Insights

- The **average IMDB rating** is around **6.7**
- Only a small percentage of movies achieve ratings above **8**
- **Drama-based genres** dominate top-rated categories
- Ratings show slight variation across different years

---

## 🚀 Skills Demonstrated

- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Data Visualization (Matplotlib, Seaborn)
- Business Dashboarding with Power BI
- Insight Generation & Reporting

---

## ▶️ How to Run the Project

1. Clone this repository

2. Install required libraries:

```bash
pip install -r requirements.txt
```

3. Open IMDB_Movie_Analysis.ipynb in Jupyter Notebook

4. Run cells sequentially to reproduce the analysis

---

## 📄 Dataset Disclaimer

The **IMDB movie** dataset used in this project is intended for **educational** and **learning purposes** only.

---

## 🧑‍💻 Author

**👤 Harsh Belekar**  
📍 Data Analyst | Python | SQL | Power BI | Excel | Data Visualization  
📬 [LinkedIn](https://www.linkedin.com/in/harshbelekar) | 🔗[GitHub](https://github.com/Harsh-Belekar)

📧 [harshbelekar74@gmail.com](mailto:harshbelekar74@gmail.com)
