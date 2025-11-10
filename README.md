# 🎬 Netflix Content Strategy Case Study (Data Analysis)

### 🧠 Overview  
This project analyzes Netflix’s catalog of movies and TV shows to uncover insights that can guide **content production** and **market expansion strategies**.  
Using a public dataset of Netflix titles, the analysis explores patterns across **genres, countries, release years, ratings, and creators**, helping identify which types of shows or movies perform well and where Netflix can focus future investments.

---

### 📊 Objectives  
As a Data Analyst, the goal was to answer key business questions:
- What kind of content (Movies vs TV Shows) has Netflix focused on in recent years?  
- How has Netflix’s content library evolved over time (growth, genres, and regions)?  
- What are the most popular genres and which countries produce the most content?  
- Who are the most frequent actors and directors on the platform?  
- What is the best time of year to launch new shows?  
- How can Netflix grow its subscriber base in different countries?

---

### 📁 Dataset  
**Size:** ~10,000 entries  

| Column | Description |
|---------|-------------|
| `show_id` | Unique ID for every Movie/TV Show |
| `type` | Identifier - Movie or TV Show |
| `title` | Title of the Movie/TV Show |
| `director` | Director of the Movie |
| `cast` | Main actors involved |
| `country` | Country where the content was produced |
| `date_added` | Date when it was added to Netflix |
| `release_year` | Original release year |
| `rating` | TV rating (e.g., PG, R, TV-MA) |
| `duration` | Duration in minutes or number of seasons |
| `listed_in` | Genre/category |
| `description` | Summary of the title |

---

### 🛠️ Tools & Technologies  
- **Python (pandas, matplotlib, seaborn)** – Data preprocessing and visualization
- **Jupyter Notebook** – Analysis documentation  

---

### 🧩 Approach  

#### 1. Data Understanding & Cleaning  
- Checked null values, duplicates, and inconsistent entries  
- Converted date columns to datetime and extracted year/month  
- Split/unnested `cast`, `director`, and `country` fields for multi-value analysis  

#### 2. Exploratory Data Analysis (EDA)  
**Univariate Analysis**  
- Distribution of titles by type (Movies vs TV Shows)  
- Most common genres and ratings  
- Yearly growth of titles added  

**Bivariate Analysis**  
- Correlation between content type and duration  
- Country vs Genre trends  
- Director/Actor collaborations and frequency  
- Time-of-year patterns for new content launches  

#### 3. Visualization  
- Countplots, boxplots, and histograms for categorical and numerical analysis  
- Trend charts for titles released per year and per region  
- Heatmaps for correlation and regional content density  

---

### 📈 Key Insights  

| Area | Insight |
|------|----------|
| **Content Type** | Netflix has increased focus on TV Shows since 2017, aligning with binge-watching trends. |
| **Regional Production** | USA, India, and UK dominate content production, but non-English titles are rising. |
| **Genre Mix** | Dramas, Comedies, and Documentaries are the most represented genres. |
| **Actors/Directors** | Certain directors have multiple successful titles; recurring talent correlates with engagement. |
| **Launch Timing** | Most content is added between Q3–Q4, aligning with holiday season and viewer spikes. |

---

### 💡 Business Recommendations  

1. **Focus on regional storytelling:** Increase investment in local content for growing markets (India, Korea, Spain).  
2. **Expand high-performing genres:** Drama and Documentary continue to attract global audiences.  
3. **Strengthen long-form series:** TV Shows show higher growth and engagement than movies.  
4. **Optimize launch schedules:** Align new releases with regional holidays and global Q4 peak periods.  
5. **Talent partnerships:** Re-engage directors and actors with proven track records to ensure consistent viewer interest.

---
