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

##installation
## Installation

Follow these steps to set up the project locally:

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/yourusername/movie-recommendation-system.git
