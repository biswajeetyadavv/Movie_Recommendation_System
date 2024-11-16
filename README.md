# Movie Recommendation System

A **Movie Recommendation System** that leverages collaborative and content-based filtering techniques to suggest movies based on user preferences. Built with Python, this system uses **Streamlit** to provide an interactive user interface and **TMDb API** to fetch movie posters.

## Features

- Personalized movie recommendations based on the selected movie.
- Displays movie posters for each recommendation.
- User-friendly web interface powered by **Streamlit**.
- Recommendation based on **collaborative filtering** and **content-based filtering**.

## Table of Contents

1. [Project Description](#project-description)
2. [Features](#features)
3. [Requirements](#requirements)
4. [Installation](#installation)
5. [Usage](#usage)
6. [How it Works](#how-it-works)
7. [License](#license)
8. [Acknowledgements](#acknowledgements)

## Project Description

This project implements a **Movie Recommendation System** using **Machine Learning**. It uses a combination of **collaborative filtering** (based on user preferences) and **content-based filtering** (based on movie metadata like genres, cast, etc.) to generate personalized movie recommendations.

The recommendation model is integrated into an interactive web application using **Streamlit**, which makes it easy for users to interact with and get movie recommendations.

## Requirements

Before running the application, ensure that you have the following dependencies installed:

- `streamlit` - For building the web application.
- `pandas` - For handling movie data.
- `pickle` - For loading pre-trained models and similarity matrices.
- `requests` - For fetching movie posters from the **TMDb API**.

You can install the required libraries using `pip`:

```bash
pip install streamlit pandas requests
```

## Installation

Follow these steps to set up the project locally:

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/yourusername/movie-recommendation-system.git
   ```
2. Navigate into the project directory:

   ```bash
   cd movie-recommendation-system
   ```
3. Install the necessary dependencies:

   ```bash
   pip install -r requirements.txt
   ```

###Usage
1. To run the app, use the following command in the terminal:

   ```bash
   streamlit run app.py
   ```
2. This will launch the Streamlit app locally.\
   You can access it in your browser at `http://localhost:8501`.

3. Once the app is up and running, you can select a movie from the dropdown list, and the system\
   will suggest similar movies along with their posters.


  ## How it Works
1. **Data**: The movie_list.pkl file contains movie metadata (e.g., titles, genres, etc.), and the similarity.pkl file stores a matrix of movie similarity scores based on 
   content or user interactions.
2. **Recommendation Logic**: When a user selects a movie, the system uses the similarity matrix to recommend the most similar movies.
3. **Movie Poster Fetching**: The TMDb API is used to fetch movie posters using the movie's unique identifier (movie ID) for better visualization.


  ## License
  This project is open source and available under the MIT License.

Acknowledgements
Streamlit - for making it easy to build interactive web applications.
TMDb API - for providing movie data and posters.
pandas, pickle, and requests - for supporting the core functionality of the application.
Special thanks to all contributors and the open-source community.
