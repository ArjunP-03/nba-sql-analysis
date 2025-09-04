# **NBA Statistics – SQL & Python Project**
# Overview

This project demonstrates the use of SQL and Python to organize, query, and analyze NBA data. It began with the Denver Nuggets’ 2025 starting five and has expanded to include multiple Western Conference playoff teams. The project highlights how to structure basketball data into relational tables and extract insights using SQL queries and Python visualizations.

# Skills Demonstrated

Database Design: Created multiple tables (PLAYERS and STATS) to store player and performance data.

SQL Queries: Performed selections, filtering, joins, and aggregations (e.g., win percentages, averages by age group).

Data Analysis in Python: Used pandas to query from SQL, clean/manipulate results, and calculate derived statistics.

Visualization: Created charts with matplotlib to compare performance across age groups and teams.

Documentation & Presentation: Clear README and reproducible notebook to showcase workflow.

# Tables

PLAYERS – Player ID, name, team, position, age.

STATS – Wins, losses, points, rebounds, assists for the 2025 playoffs.

Sample Queries

List all players with their positions and ages.

Join PLAYERS and STATS to calculate win percentages.

Compare average points, rebounds, and assists between younger (≤27) and older (>27) players.

Filter by team to analyze “Big 3” playoff performances.

# Insights

Nuggets starting five serve as a baseline example for table design and queries.

Expanded data provides comparisons across multiple Western Conference playoff teams.

Highlights the use of SQL joins and Python visualizations to reveal trends (e.g., age-based performance differences).

How to Run

Open in Google Colab.

Execute the SQL table creation and data insertion cells.

Run provided queries using pandas to view results.

(Optional) Generate visualizations with matplotlib.

# Future Work

Add Eastern Conference playoff teams for a league-wide view.

Incorporate advanced stats (e.g., shooting efficiency, PER, on/off splits).

Build dashboards for interactive data exploration.
