# IPL Data Analysis with Apache Spark & Databricks

Analyze Indian Premier League (IPL) cricket data at scale using Apache Spark and Databricks. This project demonstrates how to ingest, clean, transform, analyze, and visualize IPL datasets using PySpark in a Databricks notebook environment.

---

## **Features**

- End-to-end IPL data analysis pipeline using PySpark
- Data ingestion from CSV or Amazon S3
- Data cleaning, type conversion, and aggregation
- Calculation of key cricket statistics (runs, averages, win rates, dismissals, etc.)
- Team, player, and venue performance analysis across IPL seasons
- Visualizations for actionable insights (requires matplotlib/seaborn)
- Optimized for distributed computing with Spark

---

## **Requirements**

- Python 3.x
- Databricks Community Edition account (or Databricks cluster)
- Apache Spark (via Databricks)
- PySpark
- (Optional) matplotlib, seaborn for visualizations
- IPL dataset (ball-by-ball, matches, players, etc.; up to IPL 2017 recommended)

---

## **Setup**

1. **Create a Databricks Account & Cluster**
   - Sign up at Databricks Community Edition
   - Create a new cluster (choose latest runtime)

2. **Upload Data**
   - Upload IPL CSV files directly to Databricks, or
   - Store data in Amazon S3 and access via Spark

3. **Import Notebook**
   - Upload `IPL_DATA_ANALYSIS_SPARK.ipynb` to your Databricks workspace

4. **Attach Notebook to Cluster**
   - Open the notebook and attach it to your running cluster

---

## **How to Run**

- Run cells sequentially in the notebook to:
  - Initialize Spark session
  - Load and inspect IPL datasets
  - Clean, filter, and aggregate data
  - Perform advanced analytics (player, team, venue, match stats)
  - Generate summary tables and visualizations

---

## **Sample Analyses**

- **Team performance after winning the toss**
- **Average runs scored by batsmen in winning matches**
- **Top venues for high scores**
- **Most frequent dismissal types**
- **Player consistency and top performers**
- **Venue and season trends**

---

## **Example Output Table**

| Team                    | Toss Wins | Match Wins (after Toss) |
|-------------------------|-----------|------------------------|
| Chennai Super Kings     | 30        | 22                     |
| Mumbai Indians          | 28        | 18                     |
| Kolkata Knight Riders   | 25        | 17                     |

---

## **Customization**

- Change data source paths to match your environment (local, S3, Databricks DBFS)
- Add or modify analyses and visualizations as needed
- Extend to newer IPL seasons by updating the dataset

---

## **References & Credits**

- IPL dataset: [data.world/raghu543/ipl-data-till-2017]
- Apache Spark, Databricks documentation
- Inspired by open-source IPL Spark analysis projects.

---

## **License**

MIT License. For educational and research use.

---

**Author:**  
Avishek Bhakta  
June 2025
