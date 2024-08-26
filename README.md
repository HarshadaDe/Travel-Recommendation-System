# Travel Recommendation System

## Overview

This Travel Recommendation System is designed to help users discover new travel destinations based on their preferences. The system leverages machine learning algorithms like Collaborative Filtering and Popularity-Based Recommendation to suggest destinations that users might enjoy. The frontend is built using HTML, CSS, and JavaScript, while the backend and machine learning models are developed in Python, with the experiments and models trained in Jupyter Notebooks.

## Features

- **Collaborative Filtering**: Recommends destinations based on similarities between users.
- **Popularity-Based Recommendations**: Suggests popular destinations based on overall user ratings and visits.
- **User Interface**: A responsive and user-friendly web interface built with HTML, CSS, and JavaScript.
- **Real-Time Recommendations**: Users get recommendations instantly as they interact with the system.
- **Interactive Visualizations**: Displays user preferences and popular destinations with visual aids.

## Installation

### Prerequisites

- Python 3.x
- Jupyter Notebook
- Node.js and npm (for managing JavaScript dependencies)

### Steps

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/yourusername/travel-recommendation-system.git
    cd travel-recommendation-system
    ```

2. **Install Python Dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Install Frontend Dependencies**:
    ```bash
    cd frontend
    npm install
    ```

4. **Run the Jupyter Notebook**:
    ```bash
    jupyter notebook
    ```

5. **Start the Frontend**:
    ```bash
    cd frontend
    npm start
    ```

## Usage

1. **Data Preparation**: Load and preprocess the travel destination data in the Jupyter Notebook. You can add your dataset or use the provided sample dataset.

2. **Training the Model**: Train the collaborative filtering and popularity-based models in the notebook.

3. **Running the Web App**: Open the web app in your browser to start interacting with the recommendation system. Enter your preferences, and the system will suggest destinations.

## Algorithms

### 1. Collaborative Filtering
Collaborative Filtering works by finding similarities between users based on their past interactions. It recommends destinations by identifying users with similar tastes and suggesting locations they have liked.

- **Model**: Matrix Factorization (e.g., SVD, ALS)
- **Input**: User-Item interaction matrix (e.g., user ratings or visits to destinations)

### 2. Popularity-Based Recommendation
This approach suggests destinations based on their popularity among all users. It ranks destinations by the number of visits or average ratings.

- **Model**: Ranking based on aggregate metrics (e.g., total visits, average ratings)
- **Input**: Destination metadata (e.g., visit count, rating)



