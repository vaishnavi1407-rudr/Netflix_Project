# 📊 Netflix Data Analysis with Python

This project explores a Netflix dataset using Python to uncover insights through data cleaning and visualization. The analysis was done using *Pandas* and *Matplotlib* in *Jupyter Notebook*.

---

## 📁 Dataset
- Source: Kaggle Netflix Project.csv
- Contains information on Netflix Movies and TV Shows including type, title, country, date added, rating, duration, and release year.

---

## ✅ Project Tasks & Steps

### 1. Load and Clean the Data
- Imported the CSV file using pandas.read_csv()
- Removed missing/null values in key columns using dropna()

### 2. 📊 Bar Chart: Movies vs TV Shows
- Counted the number of *Movies* and *TV Shows*
- Found that *Movies are more than TV Shows*
- Visualized using a bar chart with custom colors

### 3. 🥧 Pie Chart: Ratings Distribution
- Created a pie chart of ratings like *TV-MA* and *TV-14*
- Found that *TV-MA* and *TV-14* are the most frequent ratings

### 4. 📉 Histogram: Distribution of Movie Durations
- Cleaned the duration column to convert it into integer minutes
- Plotted a histogram to show the distribution of movie durations
- Most movies are between *80 to 120 minutes*

### 5. 🔵 Scatter Plot: Shows per Year
- Created a scatter plot for number of shows vs release_year
- Found *2020* had the *highest number of shows released*

### 6. 🌍 Subplot: Top 10 Countries by Shows
- Analyzed the top 10 countries with the most Netflix content
- Compared Movies vs TV Shows per country using subplots
- *United States* had the highest number of both

---

## 🧰 Tools Used
- Python
- Pandas
- Matplotlib
- Jupyter Notebook

---

## 📎 Visuals
All charts were saved as images:
- movies_vs_tvshows.png
- ratings_piechart.png
- movies_duration_histogram.png
- scatter_release_year.png
- top10_countries_subplot.png

---

## 📌 Conclusion
This project demonstrates how to:
- Clean and prepare real-world data
- Use visualization to find patterns
- Compare trends like duration, type, release year, and countries
