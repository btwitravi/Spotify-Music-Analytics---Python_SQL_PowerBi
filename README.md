# 🎵 Spotify Music Analytics — End-to-End Data Project
This project is an **end-to-end data pipeline** built using **Python, SQL, Power BI**, and **ETL techniques** to analyze trends in Spotify music such as artist popularity, track performance, genre influence, album types, and yearly release patterns. The goal is to uncover meaningful insights that support **playlist curation, artist promotion**, and **content strategy**.

## 📌 Project Structure
| File / Folder | Description |
|----------------|--------------|
| `Spotify.csv` | Dataset |
| `Spotify.ipynb` | ETL + EDA Notebook (.ipynb) |
| `Spotify.pdf` | Cleaned EDA Report (PDF) |
| `Spotify.pbix` | Power BI Dashboard (.pbix) | 
| `Spotify.png` | Dashboard Screenshots |
| `Spotify_Problem.docx` | Business Problem Statement (DOCX)| 

## 🧩 1. Business Problem
Spotify hosts millions of tracks and thousands of artists, making it difficult to understand:
- Which **artists, songs, and genres** drive the most engagement
- How **album types** (single/album/compilation) perform
- Which songs achieve high **popularity scores**
- How the **music industry has evolved** year by year
- What patterns influence track performance and user listening behavior

This project analyzes Spotify data to support **data-driven decision making** for content strategy, marketing, and playlist recommendations.

## 🎯 2. Objectives
- Build a complete **ETL pipeline** for Spotify dataset
- Perform **exploratory data analysis (EDA)** to identify trends
- Understand **top-performing tracks, albums, artists, genres**
 - Analyze **distribution patterns** and **correlations**
- Study **yearly release trends** in the music industry
- Create a **Power BI dashboard** for interactive insights

## 🛠️ 3. Tools & Technologies
| Category        | Tools                                       |
| --------------- | ------------------------------------------- |
| Programming     | Python (Pandas, NumPy, Matplotlib, Seaborn) |
| Database        | MySQL (SQL queries, window functions)       |
| Visualization   | Power BI                                    |
| Data Processing | ETL pipeline, Feature Engineering           |
| Documentation   | Jupyter Notebook, PDF, DOCX                 |

## 🔄 4. ETL Process
#### ✔ Extract
Raw Spotify track dataset loaded into Python.

#### ✔ Transform
- Removed missing values
- Converted timestamp formats
- Converted duration (ms → minutes)
- Cleaned genre fields
- Formatted album release dates
- Added new features (e.g., track_duration_min, release_year)

#### ✔ Load
Final cleaned dataset exported and stored in MySQL for analysis.

## 📊 5. Exploratory Data Analysis (EDA)
#### 🔹 Distribution Insights
- **Artist followers** are highly skewed—few artists dominate.
- **Track popularity** mostly between 40–80.
- **Track duration** is normally distributed (3–5 min).
- **Track numbers** grow with album size (expected).

#### 🔹 Correlation Highlights
- Strong positive correlation between **artist popularity** and **followers** (0.64).
- Track popularity is moderately influenced by artist popularity.
- Duration has almost **no effect** on popularity.

## 🏆 6. Key Insights
#### 🎧 Top 10 Tracks
- Highest popularity score = **100**
- Tracks like The Fate of Ophelia and Golden dominate the list

#### 🎤 Top Artists (Followers)
- **Taylor Swift** leads with 145M+ followers
- Ed Sheeran, Billie Eilish, The Weeknd follow

#### 🎵 Top Genres
- Soundtrack, rap, reggaeton, and pop dominate popularity

#### 💿 Top Albums by Total Tracks
- FAIRY TAIL SOUNDTRACK ARCHIVES has **181 tracks**

#### 🌀 Album Types
- Albums: **68.6%**
- Singles: **25.6%**
- Compilations: **5.8%**

#### 📈 Yearly Trend
- Sharp increase in music releases post **2010**
- Peak releases observed after **2020**

## 📊 7. Power BI Dashboard
The dashboard includes:
- KPI Cards
- Top tracks visualization
- Genre popularity
- Artist follower rankings
- Album type distribution
- Year-wise music release trends
- Interactive filters and search
![Dashboard](images/Spotify.png)

## 🏁 8. Conclusion
This project demonstrates a complete **data analytics workflow**, from ETL to EDA to dashboard creation. The insights reveal how artist influence, genre preferences, and release patterns shape Spotify’s listening landscape. The project improves understanding of music trends and provides a foundation for recommendation engines, marketing strategies, and user engagement models.

## 🚀 9. Future Enhancements
- Apply Machine Learning to predict track popularity
-  Build a recommendation model
-  Add sentiment analysis from lyrics (if dataset available)
-   Automate daily ETL pipeline

# 🎉 **Thanks for exploring this project!**
If you like this project, ⭐ the repo and connect with me on LinkedIn.


## 👨‍💻 Author
**Ravi Kumar Gupta**  
📍 Delhi, India  

[![GitHub](https://img.shields.io/badge/GitHub-%2312100E.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/btwitravi)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230A66C2.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ravi-kumar-gupta-161745247/)

  
