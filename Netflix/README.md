# Netflix Dataset Analysis

## Project Overview
This project performs exploratory data analysis (EDA) on a Netflix dataset to uncover content distribution, genre trends, and release patterns.

---

## Objectives
- Analyze Netflix content metadata.
- Visualize distribution of shows, movies, and genres.
- Study relationships between release years and content types.
- Derive insights about platform’s catalog composition.

---

## Dataset
**File:** `netflix1.csv`  
**Rows:** ~8,791 (including header)

Common Columns:
- show_id, type, title, director, cast, country, date_added, release_year, rating, duration, listed_in, description

---

## Files Included
- `Netflix.ipynb` — Jupyter notebook with complete EDA.
- `netflix1.csv` — dataset file.

---

## Tools & Libraries
- Python 3.8+
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## How to Run
1. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn jupyterlab
   ```

2. Launch Jupyter Notebook:
   ```bash
   jupyter lab
   ```

3. Open and execute `Netflix.ipynb`.

---

## Key Insights
- The platform hosts a higher number of movies than TV shows.
- The majority of titles were added after 2015.
- The US, India, and UK contribute the largest share of content.
- Popular genres include International Movies, Dramas, and Comedies.

---

## Author & Credits
Developed by the **NSDC-JH Data Science Team** as part of the National Student Data Corps (NSDC) – JH initiative.
