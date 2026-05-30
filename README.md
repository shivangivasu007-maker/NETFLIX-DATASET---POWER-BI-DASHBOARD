# NETFLIX-DATASET---POWER-BI-DASHBOARD
TOOLS-Excel ,PowerBi, Dax ,Measures, Charts, Real Dataset ,Data Modeling , Calculated Columns ,Statistics, Visualizations. Dataset: 5,283 rows × 11 columns . An interactive Netflix Dataset Dashboard built using Power BI and Excel, analyzing 5,283 Netflix titles including Movies and TV Shows released between 1953 and 2022.

# 🎬 Netflix Dataset Dashboard — Power BI

An interactive Power BI dashboard built on a dataset of 5,283 Netflix 
titles (Movies & TV Shows), exploring IMDB scores, release trends, 
audience ratings, and content performance.

## 📊 Dashboard Overview

The dashboard consists of 6 key visualizations:

- **Type Split (Pie Chart)** — 64.49% Movies vs 35.51% Shows
- **Year-wise IMDB Score** — Trend line of total IMDB scores from 
  1950 to 2022, with forecast projection up to 2040
- **Release YOY** — Content release volume over the decades, 
  showing Netflix's explosive growth post-2010
- **Top Shows on Netflix** — Bar chart ranking titles by 
  avg_final_score, highlighting the platform's best-rated content
- **Post Review Donut** — 75.88% Average, 17% Flop, small Hit 
  segment — content quality distribution
- **KPI Cards** — Total 5,283 titles · 123M avg IMDB votes · 
  172K average total ratings

## 🛠 Tools Used

- Microsoft Power BI Desktop
- Microsoft Excel (data preparation)
- Dataset: Netflix TV Shows and Movies (CSV, 5,283 rows × 11 columns)
- Power Query (Measures,DAX,Statistics,Calculated Columns,Modeling,Visualization)

## 📁 Dataset Columns

| Column | Type | Description |
|---|---|---|
| id | String | Unique content ID |
| title | String | Title of the show/movie |
| type | String | MOVIE or SHOW |
| description | String | Plot summary |
| release_year | Integer | Year of release |
| age_certification | String | Rating (R, PG, TV-MA etc.) |
| runtime | Integer | Duration in minutes |
| imdb_id | String | IMDB reference ID |
| imdb_score | Float | IMDB rating (0–10) |
| imdb_votes | Float | Number of IMDB votes |

## 💡 Key Insights

- Netflix content volume surged dramatically after **2010**, 
  peaking around **2019–2020**
- **Movies dominate** the platform at 64.49% of all titles
- The majority of content (~76%) falls in the **Average** 
  rating category based on IMDB score
- Average total ratings stand at **172K**, showing strong 
  audience engagement on top titles

## 📌 Custom Calculated Columns (Power BI)

- `Post_review` — Classifies each title as Hit / Average / Flop 
  based on IMDB score thresholds
- `avg_final_score` — Weighted engagement score combining 
  imdb_score and imdb_votes
- Measures - ( Average total ratings,Average final score )
- Summarization in dashboard cards -(total type of shows/movies ,IMDB votes )
- Slicer for year (1943-2022)
- Charts - Pie , Line(with futuristic prediction) , Column , Donought ,Gauge ,Clustered line column chart
  

## 🚀 How to Use

1. Download the `.pbix` file
2. Open in Power BI Desktop
3. Use the `release_year` range slicer (1953–2022) to 
   filter all visuals dynamically
