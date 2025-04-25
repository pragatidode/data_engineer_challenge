# data_engineer_challenge
<<<<<<< HEAD
=======
# Overview:

This Jupyter Notebook provides a full ETL pipeline for a technical data engineering challenge:

Extract: Data is pulled from the JSONPlaceholder API.
( https://jsonplaceholder.typicode.com/)

Transform: Users and Posts are joined to create a meaningful dataset.

Load: Transformed data is first stored in PostgreSQL (staging), and then loaded into Microsoft SQL Server (warehouse).

# Technologies Used
Python 3

Jupyter Notebook

PostgreSQL (Docker)

Microsoft SQL Server (Docker)

SQLAlchemy

Pandas

Requests

# Data Sources

Users: https://jsonplaceholder.typicode.com/users

Posts: https://jsonplaceholder.typicode.com/posts

# Setup Instructions
Clone this repository:

git clone https://github.com/pragatidode/data_engineer_challenge.git
cd data_engineer_challenge

Start PostgreSQL and SQL Server via Docker (notepad docker-compose.yml/nano docker-compose.yml):
docker-compose up -d

Ensure ports and credentials match what’s used inside the notebook (e.g., PostgreSQL on localhost:5432, SQL Server on localhost:1433).

# Install Python dependencies:

pip install -r requirements.txt
Or install manually: pandas, requests, sqlalchemy, pyodbc, psycopg2

Run the Notebook:

Open etl_pipeline_notebook.ipynb in JupyterLab or Jupyter Notebook and run all cells sequentially.

>>>>>>> 3b81d7fd6ba108f27a4de25676e182246fbdc4c0
