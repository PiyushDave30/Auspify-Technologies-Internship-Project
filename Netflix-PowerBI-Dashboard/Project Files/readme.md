# 📁 Project Files

This folder describes the source files behind the **Netflix Content Analysis** Power BI dashboard, built for the **Auspify Technologies Power BI Internship**.

> 🔒 **The raw dataset and the Power BI file (`.pbix`) are not published in this repository.**
> If you would like the data or the Power BI file, or want project-related details, please contact me by **email** or **LinkedIn**.

<p align="center">
  <a href="https://www.linkedin.com/in/piyushdave30/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="https://public.tableau.com/app/profile/piyushdave/vizzes"><img src="https://img.shields.io/badge/Tableau-Public-E97627?style=for-the-badge&logo=tableau&logoColor=white"/></a>
  <a href="mailto:piyushdave3008@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <a href="https://github.com/PiyushDave30"><img src="https://img.shields.io/badge/GitHub-PiyushDave30-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
</p>

---

## 📦 Files available on request

| File | Description |
|---|---|
| `Dataset.csv` | Raw Netflix dataset (8,790 rows, 10 columns) |
| `Netflix_Final.pbix` | Final Power BI report: 5 visible pages and 2 hidden pages (Country Details and Tooltip) |
| Power Query steps | Cleaning and transformation steps, including the Genre Table |
| DAX measures | All measures used across the dashboard |

---

## 🎯 Project at a glance

| | |
|---|---|
| **Project** | Netflix Content Analysis dashboard |
| **Program** | Auspify Technologies Power BI Internship |
| **Tasks completed** | 1, 2, 3, 4 (required) and 6 (bonus) |
| **Data** | 8,502 titles, 85 countries, 42 genres, 14 years (2008 to 2021) |
| **Tool** | Power BI Desktop |

---

## 🗃️ Dataset

| Column | Description |
|---|---|
| `show_id` | Unique ID of each title |
| `type` | Movie or TV Show |
| `title` | Title name |
| `director` | Director (many values are "Not Given") |
| `country` | Country of the title |
| `date_added` | Date the title was added to Netflix |
| `release_year` | Year the title was released |
| `rating` | Audience rating (TV-MA, TV-14, PG and others) |
| `duration` | Length in minutes or number of seasons |
| `listed_in` | Genres (several genres in one cell) |

---

## 🧹 Data preparation

- Converted data types and cleaned and trimmed all text columns
- Split `duration` into a number and a unit
- Removed errors, blank rows, duplicates and the 287 rows with country "Not Given"
- Split `listed_in` into rows in a separate **Genre Table** to get the real genre counts

---

## 🗂️ Data model

| Table | Role |
|---|---|
| **Netflix Dataset** | Central data table |
| **Date Table** | Date dimension (Year, Quarter, Month, Day) |
| **Genre Table** | One row per title and genre |
| **Single Agg Measures Table** | Single-value measures (Total Titles, Total Countries, Total Genres and others) |
| **Measures Table** | Type and time measures (Total Movies, Total TV Shows, Movie %, PM Title and others) |

---

## 📊 Dashboard pages

| Page | What it covers |
|---|---|
| **Home** | Cover page with navigation buttons |
| **Overview** | KPIs, Movies vs TV Shows, genres, ratings, release years |
| **Global** | Map, top countries, Movies vs TV Shows mix, key insights |
| **Trends** | Titles added per year, drill-down, weekday pattern, release trend |
| **Executive Summary** | Four recommendations backed by numbers |
| Country Details *(hidden)* | Drill-through page |
| Tooltip *(hidden)* | Report-page tooltip on hover |

---

## 🧮 Measures

Measure groups used in the report:

- **Totals:** Total Titles, Total Movies, Total TV Shows, Total Countries, Total Genres
- **Percentages:** Movie %, TV Show %, Top Country Share, Top 5 Countries Share
- **Time intelligence:** PM Title, PM Movie, PM TV Shows, Titles Previous Year
- **Ranking and counts:** Top Country, Top 5 Countries Titles, Countries 100+ Titles, One-Title Countries
- **Averages:** Avg Titles per Country, Avg Titles per Year
- **Text measures:** custom tooltips on KPI cards

---

## ✨ Features

- Multi-page dashboard with sidebar and Home-page navigation
- Custom dark Netflix-style theme and backgrounds
- Filter Panel with bookmarks
- Drill-down (Year, Quarter, Month) and drill-through (country to Country Details)
- Report-page tooltip and measure-based tooltips on KPI cards
- Cross-filtering between visuals

---

## 🧠 Skills demonstrated

Data cleaning with Power Query · Data modelling (star-schema approach with Date and Genre tables) · DAX measures and time intelligence · Dashboard design and navigation · Data storytelling and insights

---

## 🔗 Quick links

| | |
|---|---|
| 📸 [Dashboard Screenshots](../Screenshots/readme.md) | All 10 screenshots |
| 📋 [Task Details](../Tasks/readme.md) | Task-wise workflow, measures and insights |
| 🏠 [Project Details](../readme.md) | Main project README |

## 👤 Author

**Piyush Dave** | Data Analyst
📧 [piyushdave3008@gmail.com](mailto:piyushdave3008@gmail.com) · 💼 [LinkedIn](https://www.linkedin.com/in/piyushdave30/) · 💻 [GitHub](https://github.com/PiyushDave30) · 📊 [Tableau Public](https://public.tableau.com/app/profile/piyushdave/vizzes)
