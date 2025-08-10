# Walmart Sales Analysis Project

## Overview
This project analyzes sales data from Walmart stores using Python, MySQL, and PostgreSQL. The goal is to answer key business questions, uncover insights, and demonstrate data analysis techniques using real-world retail data.

## Contents
- `Walmart.csv`: Main dataset containing Walmart sales transactions.
- `project.ipynb`: Jupyter notebook for data exploration, analysis, and visualization.
- `MySQL Queries.sql`: SQL queries for MySQL database analysis.
- `PSQL Queries.sql`: SQL queries for PostgreSQL database analysis.
- `requirements.txt`: Python dependencies and setup instructions.
- `Walmart Business Problems.pdf`: Document outlining business problems to solve.
- `Walmart Project.png`: Project-related image.

## Dataset
The dataset (`Walmart.csv`) includes:
- Invoice ID
- Branch & City
- Product Category
- Unit Price & Quantity
- Date & Time
- Payment Method
- Customer Rating
- Profit Margin

## Key Business Questions
- What are the different payment methods and their transaction counts?
- What is the quantity sold by payment method?
- Which branch has the highest-rated product category?
- What are the minimum and maximum quantities sold?
- How do profit margins vary across categories and branches?

## How to Run
1. **Install Python dependencies:**
	```bash
	pip install -r requirements.txt
	```
2. **Explore the Jupyter notebook:**
	Open `project.ipynb` in Jupyter and run the cells for step-by-step analysis.
3. **Run SQL queries:**
	Use the provided `.sql` files to analyze the data in MySQL or PostgreSQL.

## Environment Setup
See `requirements.txt` for detailed setup instructions for macOS and Windows, including Kaggle API configuration and dataset download steps.

## Requirements
- Python 3.x
- pandas, pymysql, sqlalchemy, psycopg2
- Jupyter Notebook
- MySQL or PostgreSQL (optional, for SQL analysis)

## Usage
- Modify and run the notebook to explore sales trends, answer business questions, and visualize results.
- Use SQL queries for database-driven analysis.

## License
This project is for educational and demonstration purposes.

## Author
shuvam-dinda
