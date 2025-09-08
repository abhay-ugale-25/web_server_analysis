# Web Server Logs Analysis

## Overview

This project demonstrates how to generate synthetic web server logs, load them into a SQL engine, and analyze them using SQL queries and Python visualizations. The purpose is to simulate real-world log data analysis scenarios for learning and portfolio building. It is designed to run smoothly on Google Colab, though it can also be adapted for local environments.

## Features

* Synthetic log data generation (timestamp, IP address, HTTP method, endpoint, status code, response time).
* Data loading into DuckDB for fast SQL queries.
* Six main analyses:

  1. Total number of logs.
  2. Status code distribution.
  3. Top 10 requested endpoints.
  4. Requests by HTTP method.
  5. Requests per hour.
  6. Response time distribution.
* Visualizations using matplotlib.

## File Structure

```
project_a_logs_analysis/
│
├── data/                  # Contains generated CSV logs
├── notebooks/             # Colab notebooks for log generation & analysis
├── requirements.txt       # Dependencies (for local use if needed)
├── README.md              # Project documentation
```

## Tools and Technologies

* **DuckDB**

  Used as the SQL engine to query CSV logs directly without setting up a traditional database. DuckDB is lightweight, fast, and integrates smoothly with Python and Pandas, making it ideal for local and Colab-based analysis.

* **Pandas**

  Employed for handling query outputs and preparing data for visualization. Pandas provides an easy interface for working with structured data alongside SQL.

* **Matplotlib**

  Used to create charts (bar plots, line plots, pie charts, histograms) for visualizing log analysis results. Matplotlib ensures clear and customizable visuals for exploratory data analysis.

* **Google Colab**

  Chosen as the development environment for its ease of use, zero setup, and ability to run Python notebooks in the cloud. It makes the project reproducible and accessible without requiring local installations.

### Why These Tools?

This stack was chosen to keep the project lightweight, accessible, and reproducible. DuckDB allows efficient SQL querying on raw CSV files, Pandas bridges SQL with Python workflows, and Matplotlib enables clear visual storytelling. Google Colab ensures that anyone can run the project with minimal setup, making it beginner and recruiter friendly.
