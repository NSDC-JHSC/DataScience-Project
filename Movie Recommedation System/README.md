# Movie Recommendation System (SVD Model)

## Project Overview
This project builds a movie recommendation engine using **Singular Value Decomposition (SVD)** based on the **Movielens 100k** dataset. It demonstrates the use of collaborative filtering for personalized movie recommendations.

---

## Objectives
- Understand the structure of the Movielens dataset.
- Implement an SVD-based collaborative filtering model.
- Evaluate model performance.
- Generate personalized movie recommendations.

---

## Dataset
Located under `dataset/` folder:

| File | Description |
|------|--------------|
| `u.data` | Ratings file (user_id, item_id, rating, timestamp) |
| `u.item` | Movie metadata |
| `u.genre` | Genre definitions |
| `u.user.txt` | User demographic information |

Total ratings: **100,000** records.

---

## Files Included
- `Movie_recommendation_svd.ipynb` — Jupyter notebook implementing full SVD pipeline.
- `dataset/` — contains Movielens data files.

---

## Tools & Libraries
- Python 3.8+
- Pandas
- NumPy
- Scikit-Learn
- Surprise (for SVD)
- Matplotlib
- Jupyter Notebook

---

## How to Run
1. Install dependencies:
   ```bash
   pip install pandas numpy scikit-learn scikit-surprise matplotlib jupyterlab
   ```

2. Launch Jupyter Notebook:
   ```bash
   jupyter lab
   ```

3. Open and execute `Movie_recommendation_svd.ipynb`.

---

## Model Highlights
- Uses **matrix factorization (SVD)** for latent feature discovery.
- Predicts unseen ratings for user-item pairs.
- Evaluated using **RMSE** and **MAE** metrics.

---

## Key Insights
- SVD effectively learns user and item patterns.
- Performance improves with optimized latent factor tuning.
- Dataset sparsity plays a key role in recommendation accuracy.

---

## Author & Credits
Developed by the **NSDC-JH Data Science Team** under the National Student Data Corps (NSDC) – JH initiative.
