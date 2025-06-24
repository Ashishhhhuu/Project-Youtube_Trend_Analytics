# 📈 YouTube Trending Video Analytics

This project dives deep into YouTube trending data to understand what makes content go viral. It analyzes likes, views, comments, and user sentiment across countries using a combination of SQL, Python, and Power BI. The insights help content creators, marketers, and analysts understand viewer behavior and engagement trends.

---

## 📌 Introduction

YouTube is one of the largest platforms for video sharing and content consumption globally. With millions of videos uploaded daily, it's important to understand what makes a video trend. This project analyzes trending video data across different countries (e.g., India and the US) to uncover patterns in viewer engagement and sentiment.

---

## 📄 Abstract

The goal of this project is to:
- Identify the most liked and viewed content categories
- Analyze sentiment distribution across countries
- Visualize trends using a Power BI dashboard
- Compare engagement metrics (likes, comments) based on sentiment

---

## 🛠️ Tools Used

- **Python (Jupyter Notebook)** – For preprocessing and sentiment labeling  
- **Pandas & Matplotlib** – Data manipulation and early visualization  
- **MySQL** – SQL queries for data extraction  
- **Power BI** – Interactive dashboard creation

---

## 🧰 Steps Involved in Building the Project

### 1. **Data Loading and Cleaning**
- Loaded a cleaned dataset of trending YouTube videos.
- Removed duplicates and missing values.
- Mapped category IDs to readable category names.

### 2. **Sentiment Labeling**
- Labeled each video/comment with **positive**, **neutral**, or **negative** sentiment.
- This helped measure the impact of sentiment on engagement.

### 3. **SQL-Based Data Analysis**
- Wrote SQL queries to:
  - Rank categories by average views
  - Analyze sentiment distribution per country
  - List top trending videos by views

### 4. **Power BI Dashboard**
- Built a dashboard with:
  - Pie chart for likes by sentiment
  - Line chart for likes by country
  - Donut chart for comment counts by country
  - Bar chart for likes vs comment count by sentiment
  - Card and gauge to display total comment counts

### 5. **Insight Interpretation**
- Neutral content received the highest likes
- US had more total engagement than India
- Videos with **neutral** and **positive** sentiment performed better

---

## ✅ Conclusion

This end-to-end analysis of YouTube trending data revealed key insights about content performance across countries and sentiment types. With SQL, Python, and Power BI, the project enabled meaningful, data-driven conclusions for better content strategy planning.

---

## 📁 Repository Contents

- `Youtube_Video_Analysis.ipynb` – Python notebook for exploration and sentiment prep  
- `Youtube_Analytics.sql` – SQL queries used for analysis  
- `Youtube_Trend_Analysis.png` – Power BI dashboard snapshot  
- `YouTube_Trending_Video_Analytics_Report.pdf` – Full project report  
- `README.md` – Project documentation  

---

## 🙋🏻‍♂️ Author

**Ashish Shabolu**  
🎓 B.Tech Data Science  
📍 India  
🐙 [GitHub](https://github.com/Ashishhhhuu)

---
