# Movie Recommender System (TMDB Dataset)

This repository contains the implementation of a simple movie recommender system using the TMDB (The Movie Database) dataset.
This project was developed as part of my semester project.


## Prerequisites

Ensure you have the following installed on your system:

- Python (Version 3.8 or later)
- pip (Python package manager)
- Git (to clone the repository)

## How to Run This Project on Your PC

Follow these steps to set up and run the Movie Recommender System on your local machine:

### 1. Clone the Repository
Clone the project repository from GitHub:

```bash
git clone https://github.com/Ayushcode10/movie-recommender-system-tmdb-dataset.git
cd movie-recommender-system-tmdb-dataset
```
 ## 2. Install Required Dependencies
 ```bash
pip install -r requirements.txt
 ```
## 3. Download the Dataset
Download the TMDB 5000 Movies and Credits dataset from Kaggle.
Place the downloaded CSV files <mark>(tmdb_5000_movies.csv and tmdb_5000_credits.csv)</mark>in the dataset folder within the project directory.

## 4. Run the Application
```bash
streamlit run app.py
```

## 5. Access the Application
Once the app starts, you will see a URL in the terminal (e.g., <mark>http://localhost:8501</mark>).
Open this URL in your web browser to use the Movie Recommender System.

## 5. Troubleshooting
File Not Found Errors: Ensure all datasets are placed in the correct folder (dataset).
Dependency Issues: Run <mark>pip install -r requirements.txt</mark> again to resolve missing dependencies.
Port Conflicts: If the app fails to start, check if port 8501 is in use or specify a different port:
```bash
streamlit run app.py --server.port 8502
```
## Acknowledgments
TMDB dataset is available on Kaggle.
The recommender system is based on collaborative and content-based filtering techniques.
