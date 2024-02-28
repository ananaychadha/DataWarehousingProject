# DataWarehousingProject

## Project Details

- **Project Files:**
  - `DW_dataset.csv`: Data file for Q1.
  - `input_DW_data.csv`: Data file for Q2.
- **Expected Output Files:**
  - `Practical-02.ipynb`: Python notebook solutions.
  - `Practical-02.html`: Python notebook in HTML format.
- **Requirements:**
  - Python 3.9+
  - pandas 1.3+
  - SQLAlchemy 1.4+
  - mlxtend 0.20

## Project Overview

This practical aims to develop data warehouses for data-driven applications using PostgreSQL database, Python, and its libraries. The assignment focuses on applying concepts and techniques discussed in lectures to define and set up a data warehouse for a specific data-driven application. The tasks are to be solved in Python using the provided packages.

## Data Preprocessing and OLAP Queries

- **Data Cube (Q1):** Preprocess the given dataset (`DW_dataset.csv`) about a set of employees in a company. Clean the data, create a PostgreSQL database, and perform OLAP queries to answer specific questions.
- **OLAP Queries (Q2):** Perform OLAP queries on PostgreSQL using SQLAlchemy to answer questions about average salary calculations, employee counts, and retention rates.

## Data Warehouse Implementation

- **Snowflake Schema (Q1):** Design a snowflake schema diagram for a data warehouse consisting of dimensions like student, course, semester, and instructor, and measures like count and avg_grade.
- **OLAP Operations (Q2):** Identify specific OLAP operations, such as roll-up and drill-down, to list the average grade of CS courses for each student.

## How to Run

1. Clone the repository to your local machine.
2. Download the `DW_dataset.csv` and `input_DW_data.csv` files into the project directory.
3. Install the required Python packages: pandas, SQLAlchemy, mlxtend.
4. Open the `Practical-02.ipynb` notebook and run each cell to execute the code.

## Conclusion

This project demonstrates the application of data warehousing concepts using PostgreSQL, Python, and relevant libraries. It covers data preprocessing, schema design, and OLAP query execution, providing a comprehensive overview of data-driven applications. The tasks emphasize practical skills essential for effective database management and analysis. Overall, this project offers a practical understanding of data warehousing techniques and their implementation.
