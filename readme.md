### 🎬 Movie Recommendation Systems – Machine Learning Project
This is a machine learning project focused on building and comparing multiple movie recommender systems using the MovieLens 1M dataset.
Developed as part of the Practical Data Science course at RMIT University, it demonstrates the application of supervised and unsupervised learning principles in real-world recommendation tasks.

### 🧠 Project Overview
The goal of this project was to design, implement, and evaluate several recommendation algorithms and analyse how model complexity affects performance and personalisation.
Three approaches were explored:
- User-Based Collaborative Filtering – traditional similarity-based method using nearest neighbours.
- Item-Based + Content Hybrid Filtering – integrates collaborative filtering with content features (genres).
- Modern Recommender (Matrix Factorisation / FunkSVD) – a machine-learning model that learns latent user and item representations for personalised predictions.
  
Each system was evaluated with quantitative metrics (RMSE, Average Precision, NDCG) to compare their predictive accuracy and ranking quality.

### 📊 What This Project Demonstrates
- Application of machine learning techniques in recommender-system design.
- Comparative analysis of baseline, hybrid, and latent-factor models.
- End-to-end pipeline: data preprocessing → model training → evaluation → visualisation.
- Insights on how model-based learning (FunkSVD) outperforms similarity-based approaches in sparse data scenarios.

### 🧩 Tech Stack
- Python, NumPy, Pandas, Scikit-Learn, Matplotlib, Seaborn
- Jupyter Notebook for development and reproducibility
- Dataset: MovieLens 1M (GroupLens Research)

### 🏁 Outcome
The project highlights how evolving from simple neighbourhood methods to machine-learning-based matrix factorisation significantly improves recommendation accuracy and personalisation — similar to the techniques powering platforms like Netflix, Spotify, and YouTube.
