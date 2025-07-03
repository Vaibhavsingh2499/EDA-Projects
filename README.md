# EDA-Projects
#  Netflix Titles Dataset: Exploratory Data Analysis (EDA)

This project explores Netflix's content catalog to uncover patterns, trends, and business insights using exploratory data analysis techniques. We clean and prepare the data, create visualizations, and generate insights to inform decisions like content strategy, genre trends, and actor partnerships.

---

## 🎯 Objectives

- Understand the distribution of Movies vs TV Shows
- Analyze content rating distribution
- Identify country-wise content contributions
- Visualize content addition trends over the years and months
- Determine the most frequent actors and creators on Netflix
- Explore genre and duration-based patterns
- Deliver actionable business insights

---

## 📦 Dataset Information

- **Source**: [Netflix Titles Dataset - Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- **Rows**: ~8800
- **Features**: title, type, director, cast, country, date_added, rating, duration, listed_in (genre), description

---

## 🧰 Tools & Libraries

- Python
- Pandas, NumPy
- Seaborn, Matplotlib, Plotly
- Jupyter Notebook

---

## 🔧 EDA Workflow

### 1. 📥 Data Loading & Inspection
- Loaded `.csv` file using pandas
- Inspected structure, data types, and summary statistics

### 2. 🧹 Data Cleaning
- Handled missing values in `director`, `cast`, `country`, `rating`
- Dropped the unused `description` column
- Converted `date_added` to datetime, extracted `year_added` and `month_added`
- Checked and removed duplicates

### 3. 📊 Univariate Analysis
- Count of Movies vs TV Shows
- Top 10 countries contributing content
- Rating-wise content distribution
- Genre frequency
- Distribution of movie durations

### 4. 🔁 Bivariate & Trend Analysis
- Year-wise content addition trend
- Month-wise and seasonal content patterns
- Type vs Rating comparison
- Genre vs Content Type
- Country vs Type heatmap

### 5. 🎭 Cast & Creator Analysis (Bonus)
- Exploded multi-actor cast column
- Counted top 15 most frequent actors on Netflix
- Identified top 15 directors/creators by content count

---

## 📈 Key Insights

- 🎬 About 70% of Netflix content is movies, the rest are TV Shows.
- 🌍 The USA, India, and the UK dominate content contribution.
- 🕒 Content addition peaked between 2018–2020.
- 🧑‍🎤 Actors like Anupam Kher and Radhika Apte frequently appear in multiple Netflix titles.
- 🎬 Directors such as Jan Suter and Raoul Peck contribute often.
- ⏱️ Most movies are 80–120 minutes long, suggesting a typical Netflix movie runtime.
- 🔞 Ratings like TV-MA and TV-14 are the most common.

---
