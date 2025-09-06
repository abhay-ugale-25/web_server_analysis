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
├── notebook/             # Colab notebooks for log generation & analysis
├── requirements.txt       # Dependencies (for local use if needed)
├── README.md              # Project documentation
```


