# Youtube_Data-End-to-End-Project
This project automates the end-to-end pipeline of YouTube data extraction using the YouTube API. Python and AWS is used to manage the ETL (Extract, Transform, Load) workflow. The cleaned and transformed data is stored in Amazon RDS using PostgreSQL. Power BI is used for dashboards and visualize key metrics like views, likes.

---

## 📖 Project Overview

This project is designed to automate the process of fetching YouTube channel data, cleaning and transforming it, storing it in a database, and optionally visualizing key insights.

Whether you're a data enthusiast, student, or someone building a portfolio — this project showcases the fundamentals of a **data pipeline**, with each step coded in Python and explained clearly.

---

## ⚙️ Tech Stack

| Purpose        | Technology              |
|----------------|--------------------------|
| Language       | Python                  |
| API Access     | YouTube Data API v3     |
| Data Storage   | MongoDB / PostgreSQL    |
| Visualization  | PowerBi Desktop    |
| Environment    | `venv` (Virtual Environment) |
| Secrets Mgmt   | `.env` file using `python-dotenv` |

## Features

Securely loads YouTube API credentials
Extracts real-time data from channels
Upload the data onto S3 bucket.
Cleans & transforms using Python logic
Connected AWS RDS to get transformed data and integrated with postgres
Loads to a database (Postgres) 
Used PowerBI to create interactive dashboards to visualize data.

## Dashboards

![image](https://github.com/user-attachments/assets/f1cae4aa-39de-4c01-95da-b4496998c02a)<br>

![image](https://github.com/user-attachments/assets/0add92e2-d3ce-402b-9399-8f7a30446e0f)<br>

![image](https://github.com/user-attachments/assets/4f30acfb-b049-4f52-87e6-69084e53d296)





