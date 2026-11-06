# SQL Summative Lab: Business Intelligence & Movie Data Analysis

## Project Overview

This project demonstrates the use of SQL and Python for data extraction, business analysis, and exploratory data analysis.

The project is divided into two main parts. The first focuses on analysing customer, sales, payment, and product data for a wholesale model company. The second explores movie industry data from IMDb, investigating relationships between movie runtimes, genres, and audience ratings.

The objective is to demonstrate how SQL queries can be used to answer business questions, identify patterns, and generate insights to support data-driven decision-making.

## Tools and Technologies

- **SQL (SQLite):** Data querying, filtering, aggregation, joins, and subqueries.
- **Python:** Data analysis and database interaction.
- **Pandas:** Data manipulation and analysis.
- **Matplotlib:** Data visualisation.
- **Seaborn:** Statistical data visualisation.
- **Jupyter Notebook:** Analysis and documentation.

## Part 1: Business and Customer Data Analysis

The first part focuses on analysing a wholesale company's customer and product database.

### Business Questions and Analysis

The project addresses the following business requirements:

1. **California Customer Targeting:** Identify California customers with credit limits exceeding $25,000 for targeted promotional campaigns.

2. **International Collectable Campaign:** Identify international customers whose names contain the word "Collect".

3. **Credit Limit Analysis:** Calculate average customer credit limits across US states to support credit policy and inventory decisions.

4. **Top 10 Customers:** Identify the company's top ten customers based on total payments made.

5. **Customer Product Preferences:** Identify products purchased in quantities of ten or more by individual customers.

6. **Product Line Performance:** Examine product variety and total quantities ordered across different product lines.

7. **Remote Office Analysis:** Identify employees working in offices with fewer than five employees, including their job titles and supervisors.

### SQL Concepts Applied

- SELECT and FROM
- WHERE and conditional filtering
- GROUP BY and HAVING
- ORDER BY and LIMIT
- INNER JOIN and LEFT JOIN
- Aggregate functions (SUM, COUNT, AVG)
- Subqueries
- DISTINCT
- SQL string operations

### Visualisations

The analysis includes:
- Bar chart showing average customer credit limits by US state.
- Bar chart highlighting the top ten customers by total payments.
- Scatter plot examining the relationship between product variety and total quantity ordered.

## Part 2: IMDb Movie Data Exploratory Analysis

The second part explores an IMDb movie database containing information about movies released between 2010 and 2019.

The database includes information on:
- Movie titles and release years.
- Genres.
- Runtime in minutes.
- Directors, writers, and other personnel.
- Movie ratings and number of votes.

### Database Structure

The database relationships are represented using an Entity Relationship Diagram (ERD).

The main tables include:

- `movie_basics`
- `movie_ratings`
- `movie_akas`
- `persons`
- `principals`
- `directors`
- `writers`
- `known_for`

### Exploratory Analysis Questions

**1. Movie Runtime vs. Average Rating**

Investigates how movie duration relates to audience ratings by grouping movies into runtime categories and calculating their average IMDb ratings.

**2. Genre Performance and Production Volume**

Identifies genres with the highest average ratings while considering the number of movies produced in each genre.

The analysis uses SQL aggregation and filtering to focus on genres with more than 20 movies.

### Visualisation

A bar chart is used to compare average IMDb ratings across the top-rated genre combinations.

## Data Analysis Approach

The project follows a structured analytical process:

1. Understand the business requirements and available datasets.
2. Explore database structures and relationships.
3. Develop SQL queries to answer business questions.
4. Extract query results into Pandas DataFrames.
5. Perform aggregations and filtering.
6. Visualise important findings using Python libraries.
7. Interpret the results to support business decision-making.

## Key Learning Outcomes

Through this project, I strengthened my ability to:

- Translate business requirements into SQL queries.
- Retrieve and analyse data from relational databases.
- Work with multiple database tables using SQL joins.
- Apply aggregate functions and subqueries.
- Use Python and Pandas alongside SQL.
- Create meaningful data visualisations.
- Explore relationships and patterns in real-world datasets.
- Communicate analytical approaches through structured documentation.

## Project Files

- `SQLSummativeLab.ipynb` – Main notebook containing SQL queries, Python analysis, and visualisations.
- `movie_data_erd.jpeg` – Entity Relationship Diagram illustrating the IMDb database structure.

## Conclusion

This project demonstrates practical applications of SQL and Python in business intelligence and exploratory data analysis.

By combining relational database querying, data manipulation, and visualisation, the analysis provides a foundation for understanding customer behaviour, product performance, and patterns in movie ratings.

**Skills demonstrated:** SQL | Python | SQLite | Pandas | Data Analysis | Data Visualisation | Business Intelligence | Exploratory Data Analysis.
