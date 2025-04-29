<p align="center">
  <img src="mv_recommendation_system_image.png" width="100%"/>
</p>




# 🎬 Movie Recommendation System

This is a **content-based movie recommendation system** built using **cosine similarity**. The app allows users to select a movie, and it recommends similar movies based on content features such as genres, keywords, and other metadata.

## 🚀 Project Demo

[Live Demo ](https://your-deployment-link.com)

## 📌 Features

- Built with **Streamlit** for a simple and interactive web UI.
- Uses **cosine similarity** to recommend top 5 similar movies.
- Preprocessed data using **pandas** and **scikit-learn**.
- Recommends movies based on textual similarity between movie features.

## 🧠 Technologies Used

- Python
- Streamlit
- Pandas
- Scikit-learn
- Pickle (for saving preprocessed data)

## 📂 Project Structure

```plaintext
movie-recommendation-system/
├── app.py                     # Streamlit app script
├── movies.csv                 # Movie metadata file
├── similarity.pkl             # Pickle file containing cosine similarity matrix
├── movies_dict.pkl            # Pickle file with movie metadata dictionary
├── requirements.txt           # List of dependencies
├── README.md                  # Project documentation
└── .gitignore                 # Files and folders to ignore in Git

