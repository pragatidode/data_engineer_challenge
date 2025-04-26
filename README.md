# data_engineer_challenge

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
# Environment setup
yml file for two containers alredy added into this repository. Use following command to start two containers.

docker-compose up -d


# Install Python dependencies:

pip install -r requirements.txt
Or install manually: pandas, requests, sqlalchemy, pyodbc, psycopg2

Run the Notebook:

Open etl_pipeline_notebook.ipynb in JupyterLab or Jupyter Notebook and run all cells sequentially.

