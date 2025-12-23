# 🎬 IMDb Movie Revenue Analysis

An end-to-end data analytics project built using **Python, SQL Server, and Power BI** to analyze movie revenue, IMDb ratings, and genre trends.  
The project demonstrates a complete analytics workflow — from raw data cleaning and exploratory analysis to database storage and interactive dashboard visualization.

---

## 📌 Project Objective

The goal of this project is to:
- Analyze **movie revenue, ratings, and genres**
- Identify **high-performing film trends**
- Understand whether **higher IMDb ratings lead to higher revenue**
- Build a **professional, interactive Power BI dashboard** for business insights

---

## 🧰 Tech Stack

- **Python** (Pandas, NumPy, Matplotlib, Seaborn)
- **SQL Server** (data storage & analytical queries)
- **Power BI** (dashboard & visualization)
- **DAX** (measures and KPIs)

---

## 📊 Dataset

- Source: IMDb Movies Dataset
- Size: ~9,700 movie records
- Key fields:
  - Movie title
  - IMDb rating
  - Genre (multi-genre)
  - Budget
  - Revenue
  - Country
  - Release year

---

## 🔄 Project Workflow

### 1️⃣ Data Collection & Cleaning (Python)
- Loaded raw IMDb dataset using Pandas
- Cleaned missing values and corrected data types
- Converted IMDb ratings to proper decimal scale
- Split and normalized multi-genre values
- Engineered new features:
  - **Profit** (Revenue − Budget)
  - **Rating Category** (Low / Medium / High)

---

### 2️⃣ Exploratory Data Analysis (EDA)
- Analyzed distributions of ratings, revenue, and budget
- Performed **correlation analysis** between ratings, revenue, and profit
- Identified skewness and outliers in revenue data
- Explored genre-wise performance using aggregations and visualizations

---

### 3️⃣ Data Storage & Analytics (SQL Server)
- Loaded cleaned data into **SQL Server**
- Designed a structured `Movies` table
- Executed analytical SQL queries using:
  - `GROUP BY`
  - Aggregations
  - Filtering
  - Trend analysis
- Prepared data for BI consumption

---

### 4️⃣ Dashboard & Visualization (Power BI)
Built an interactive Power BI dashboard featuring:
- KPI cards (Total Revenue, Average Rating, Movie Count)
- Revenue performance by genre
- IMDb Rating vs Revenue scatter analysis
- Revenue trends over time
- Top-performing movies table
- Interactive slicers:
  - Genre
  - Release Year
  - Rating Category

Advanced visualization techniques used:
- Quadrant analysis using reference lines
- Log-scale revenue visualization
- Transparency and size tuning to handle overplotting

---

## 📈 Key Insights

- High IMDb ratings **do not guarantee** high revenue
- Certain genres consistently outperform others financially
- Movie revenue follows a **winner-takes-most** pattern
- Budget and genre have a stronger impact on revenue than ratings alone
- Average-rated movies can outperform critically acclaimed films commercially

---

## 🧠 Skills Demonstrated

- Exploratory Data Analysis (EDA)
- Feature Engineering
- SQL-based Analytical Queries
- Data Modeling & Relationships
- Power BI Dashboard Design
- DAX Measures & KPIs
- Data Storytelling & Visualization Best Practices

---

## 📁 Repository Structure

