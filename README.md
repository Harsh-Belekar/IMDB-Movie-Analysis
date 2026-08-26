# 🎬 IMDB Movie Analysis

A **Data Science and Data Analytics project** that analyzes IMDB movie data to uncover insights into rating distributions, top-rated movies, genre performance, and year-wise trends. The project combines **Python-based exploratory data analysis** with an **interactive Power BI dashboard** to transform raw movie data into meaningful and visually engaging insights.

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python) ![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-blue?logo=pandas) ![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-lightblue?logo=numpy) ![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange) ![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Plots-teal) ![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow?logo=powerbi) ![Data Science](https://img.shields.io/badge/Data%20Science-Project-success) ![EDA](https://img.shields.io/badge/EDA-Exploratory%20Data%20Analysis-informational) ![IMDB](https://img.shields.io/badge/Dataset-IMDB-red)

---

## 📊 Project Objectives

Using the IMDB movie dataset, this project aims to:

* Clean and preprocess raw movie data.
* Calculate summary statistics including **mean, median, and mode** of movie ratings.
* Analyze and visualize the distribution of IMDB ratings.
* Identify the **top-rated movies** based on audience ratings.
* Analyze **genre-wise average ratings**.
* Explore rating trends across different years.
* Build an interactive **Power BI dashboard** to present key findings.

---

## 🛠️ Tools & Technologies

### Programming & Data Analysis

* **Python**
* **Pandas**
* **NumPy**

### Data Visualization

* **Matplotlib**
* **Seaborn**

### Development Environment

* **Jupyter Notebook**

### Business Intelligence & Dashboarding

* **Microsoft Power BI**

### Data Format

* **CSV**

---

## 📂 Project Structure

```text
IMDB Movie Analysis/
│
├── README.md
├── requirements.txt
│
├── Dashboard/
│   └── IMDB Movie Analysis Dashboard.pbix
│
├── Data/
│   └── IMDB_Movie_Data.csv
│
├── Docs/
│   └── IMDB Movie Analysis Dashboard.pdf
│
├── Notebook/
│   └── IMDB_Movie_Analysis.ipynb
│
└── images/
    ├── Box Plot of IMDB Ratings.png
    ├── Distribution of IMDB Ratings.png
    ├── IMDB Movie Analysis Report.png
    └── Top Rated Genres on IMDB.png
```

---

## 🧹 Data Cleaning & Preprocessing

The raw IMDB dataset was cleaned and prepared before performing exploratory analysis.

### 🔹 Missing Value Handling

* **Revenue (Millions)** → Missing values replaced using the **median**.
* **Metascore** → Missing values replaced using the **mean**.

Median imputation was used for revenue because financial data can contain extreme values and the median is less sensitive to outliers.

### 🔹 Additional Preprocessing

* Converted numerical columns to appropriate data types.
* Checked the dataset for duplicate records.
* Verified data consistency before performing analysis.
* Prepared genre data for individual genre-level analysis.

---

## 📈 Exploratory Data Analysis

### 🔹 Distribution of IMDB Ratings

The rating distribution was analyzed using a histogram to understand how movie ratings are spread across the dataset.

![Distribution of IMDB Ratings](images/Distribution%20of%20IMDB%20Ratings.png)

> Most movies are concentrated within the **6–8 rating range**, indicating generally positive audience reception.

---

### 🔹 Box Plot of IMDB Ratings

A box plot was used to analyze the spread, central tendency, and potential outliers in movie ratings.

![Box Plot of IMDB Ratings](images/Box%20Plot%20of%20IMDB%20Ratings.png)

> The box plot provides a clear view of the rating distribution and highlights unusually low or high-rated movies.

---

### 🔹 Top Rated Genres

Genre-level analysis was performed by separating movies containing multiple genres and calculating the average rating for each genre.

![Top Rated Genres](images/Top%20Rated%20Genres%20on%20IMDB.png)

> The analysis highlights the genres with stronger average audience ratings and provides insight into genre-level performance.

---

## 📊 Power BI Dashboard

An **interactive Power BI dashboard** was developed to provide a consolidated view of the movie dataset and make the analysis easier to explore.

### 🔹 Dashboard Highlights

* 🎬 **Total Movies** KPI
* ⭐ **Average Rating** KPI
* 🏆 **Highest Rating** KPI
* 📊 IMDB rating distribution
* 🎭 Top-rated genres
* 🎥 Top-rated movies
* 📈 Year-wise average rating trend
* 🔎 Interactive filters for:

  * Year
  * Genre
  * Rating

![IMDB Power BI Dashboard](images/IMDB%20Movie%20Analysis%20Report.png)

### 📁 Dashboard Files

* `IMDB Movie Analysis Dashboard.pbix` — Power BI source/dashboard file.
* `IMDB Movie Analysis Dashboard.pdf` — PDF export of the dashboard.

---

## 📌 Key Insights

### ⭐ Rating Distribution

Most movies in the dataset have IMDB ratings between **6 and 8**, showing that the majority of movies received moderate to strong audience ratings.

### 🏆 Top-Rated Movies

Movies with ratings above **8** represent a smaller portion of the dataset, highlighting the relative rarity of exceptionally high-rated movies.

### 🎭 Genre Performance

Genre-level analysis reveals differences in average audience ratings across movie categories, helping identify genres that perform strongly in terms of audience reception.

### 📈 Year-Wise Trends

The year-wise analysis provides an overview of how average movie ratings vary across different release years.

### 📊 Interactive Analysis

The Power BI dashboard allows users to dynamically filter the analysis by **year, genre, and rating**, making it easier to explore specific segments of the dataset.

---

## 🚀 Skills Demonstrated

* Data Cleaning & Preprocessing
* Exploratory Data Analysis (EDA)
* Statistical Analysis
* Missing Value Imputation
* Data Transformation
* Data Visualization
* Python Data Analysis
* Pandas & NumPy
* Matplotlib & Seaborn
* Power BI Dashboard Development
* KPI Development
* Data Storytelling
* Insight Generation & Reporting

---

## ▶️ How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/IMDB-Movie-Analysis.git
```

### 2. Navigate to the Project Directory

```bash
cd IMDB-Movie-Analysis
```

### 3. Install Required Python Libraries

```bash
pip install -r requirements.txt
```

### 4. Open the Jupyter Notebook

Open:

```text
Notebook/IMDB_Movie_Analysis.ipynb
```

using Jupyter Notebook or JupyterLab.

### 5. Run the Notebook

Run the notebook cells sequentially to reproduce the data cleaning, statistical analysis, exploratory data analysis, and visualizations.

### 6. Explore the Power BI Dashboard

Open:

```text
Dashboard/IMDB Movie Analysis Dashboard.pbix
```

in **Microsoft Power BI Desktop** to explore the interactive dashboard.

---

## 📄 Dataset Disclaimer

The **IMDB movie dataset** used in this project is intended for **educational and learning purposes**.

The analysis presented in this repository is for demonstration of data analysis, visualization, and dashboard development techniques.

---

## 🧑‍💻 Author

**👤 Harsh Belekar**  
📍 Data Analyst | Python Developer | SQL | Power BI | Excel | Data Visualization  
📬 [LinkedIn](https://www.linkedin.com/in/harshbelekar) | 🔗[GitHub](https://github.com/Harsh-Belekar)

📧 [harshbelekar74@gmail.com](mailto:harshbelekar74@gmail.com)

---

⭐ *If you found this project helpful, feel free to star the repo and connect with me for collaboration!*
