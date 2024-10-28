# Movie Recommendation System

Welcome to the Movie Recommendation System! This project provides personalized movie recommendations using a content-based approach, relying on cosine similarity to suggest movies based on features such as genres, keywords, cast, and crew which is combine in one text and it given to model.  

There are mainly there type of recommend system :  

- **1**: Content Recommendation Systems
- **2**: Collaborative Recommendation Systems
- **3**: Hybrid Recommendation Systems

## 🚀 Project Overview

This Movie Recommendation System leverages a content-based filtering approach to provide personalized movie suggestions. The system processes a dataset of 5,000 movies and uses CountVectorizer to extract features from metadata fields such as genres, keywords, cast, and crew. It then calculates cosine similarity between movies to find the most relevant recommendations. Given a movie name, the system outputs the top five similar movies based on the highest similarity scores, offering users tailored movie suggestions.

https://github.com/user-attachments/assets/aa855b14-2114-4678-ac39-b7fff868f0c6

## 🎯 Features

- **Content-Based Filtering**: Recommendations are based on the movie's metadata, including genres, keywords, cast, and crew.
- **Efficient Text Processing**: Preprocessing steps include parsing and converting text features for similarity calculations.
- **Cosine Similarity**: Measures the similarity between movies based on their feature vectors, ensuring relevant suggestions.
- **User-Friendly Interface**: A responsive web interface built with Streamlit makes interaction easy and intuitive.
- **Docker Integration**: Simplifies deployment with Docker, allowing you to run the system in a containerized environment.

## 🛠️ Technologies Used

- **Python**: For data processing, feature engineering, and running the recommendation system.
- **Pandas**: Efficient data manipulation and handling.
- **Scikit-Learn**: Provides tools for vectorization and cosine similarity calculations.
- **Streamlit**: Builds a simple and interactive web interface.
- **Docker**: Packages the application for easy deployment.

## 📂 Project Structure

├── Movie.csv                # Csv data for app  
├── app.py                   # Main application script for running the Streamlit app  
├── Movie-Recommand.ipynb/   # Contains the recommendation model files after run will get two pickel file  
├── Dockerfile               # Docker setup for easy deployment  
├──.dockerignore             # file that don't want to take in docker image  
├── requirements.txt         # Dependencies required for running the project  
└── README.md                # Project overview and information  

## 🤝 Contributing

Contributions are welcome! Please feel free to open issues or pull requests for improvements.




