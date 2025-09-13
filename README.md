# Netflix Dataset Analysis

## Overview

Analyze Netflix content using **Python, Pandas, NumPy, Matplotlib, and Seaborn**. Explore trends, statistics, and create new features.

---

## Dataset

* **File:** `netflix_titles.csv`
* **Records:** 8,807 | **Columns:** 12
* **Key Columns:** `type`, `title`, `director`, `cast`, `country`, `release_year`, `rating`, `duration`, `listed_in`

---

## Analysis Performed

* **Basic Data Understanding:** shape, columns, missing values, duplicates, unique values.
* **EDA:**

  * Movies vs TV Shows count
  * Top 10 countries and genres
  * Release year trends and movie durations
  * Titles added per year
* **Statistics:** mean, median, mode, variance, standard deviation, percentage of recent titles
* **Feature Engineering:** `content_age`, `is_movie`, `recent_release`, `num_genres`, release year quartiles
* **SQL-like Queries:** filter movies after 2015, top countries, titles between 2000–2010, count of Drama titles

---

## Insights

* **Most content country:** United States
* **Year with most releases:** 2018
* **Most frequent type:** Movie
* **Most common genre:** International Movies
* **Average content age:** 10.82 years
* **Titles with 3+ genres:** 42.34%

---

## How to Run

1. Install packages:

```bash
pip install pandas numpy matplotlib seaborn
```

2. Place `netflix_titles.csv` in your directory.
3. Run the Python script or notebook.


