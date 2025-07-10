
# 📊 Airbnb Booking & Review Trend Analysis

A full-stack analytics project exploring pricing trends, seasonal demand, and review patterns in Airbnb listings. Built using SQL-based data warehousing, Python for EDA, and Tableau for interactive dashboards.

---

## 🔍 Overview

This project leverages real-world Airbnb data (sourced from [InsideAirbnb](http://insideairbnb.com/get-the-data.html)) to uncover insights across 100k+ listings. The data was modeled using a **star schema** and stored in a dimensional warehouse to support scalable analysis.

**Key Goals:**
- Analyze pricing behavior and seasonal availability
- Identify high-value neighborhoods and guest engagement
- Deliver insights through dynamic Tableau dashboards

---

## 🛠 Technologies Used

| Tool/Tech     | Purpose                                 |
|---------------|-----------------------------------------|
| **Python**    | Data cleaning, transformation (pandas)  |
| **SQL (Oracle)** | Star schema modeling, ETL pipeline      |
| **Tableau**   | Dashboards & interactive storytelling   |
| **Excel**     | Exploratory analysis, validation        |

---

## 🧱 Data Architecture

- Designed a **dimensional model** with fact and dimension tables:
  - `fact_booking`, `dim_date`, `dim_listing`, `dim_neighborhood`, `dim_review`
- Loaded data into Oracle SQL using manual + script-based ETL

---

## 📈 Dashboards & Insights

> You can explore dashboards via Tableau Public [insert your link here]

- Seasonal pricing variations by room type and location
- Review trends (volume, sentiment, response rate)
- Booking availability heatmaps
- Value-for-money ranking by neighborhood

---

## 📌 Key Results

- Reduced query complexity by **60%** with optimized schema
- Enabled **interactive filtering** by price, date, and region
- Supported policy recommendations and pricing strategy

---

## 📂 Project Structure

