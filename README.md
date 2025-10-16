# Movie Recommendation System

**Author:** Shashank Pratap

## Overview
This project is a **hybrid movie recommendation system** that combines **user personalization** with key **movie features** like **genre, ratings, year of release, and popularity**. It is designed to provide accurate, diverse, and balanced movie suggestions.

## Dataset
- [MovieLens](https://grouplens.org/datasets/movielens/)  
- [The Movie Database (TMDb)](https://www.themoviedb.org/)

## Models Implemented
- **Popularity-based model**  
- **Content-based model** (genre, year, ratings)  
- **Collaborative Filtering (User-Item, KNN similarity)**  
- **Latent Factor Model (SVD)**  
- **Combined Linear Model (CF + SVD using Surprise library)**  
- **Hybrid Model** (content-based + popularity + item-item CF + SVD)

## Features
- Personalized movie recommendations  
- Integration of multiple recommendation techniques  
- Evaluation using **RMSE, MAE, Precision, Recall, F-measure, NDCG**  
- Hyperparameter tuning and detailed performance analysis

## Technologies Used
- **Python**  
- **pandas**  
- **scikit-learn**  
- **Surprise library**

## How to Run
1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/your-repo.git
