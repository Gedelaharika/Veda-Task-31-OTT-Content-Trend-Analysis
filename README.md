# Veda Task 31 – OTT Streaming Content Trend Analysis

## Objective

Analyze Netflix, Amazon Prime, and Disney+ Hotstar content catalogs to identify trends in genres, ratings, content types, and release years, and provide actionable content strategy insights.

## Datasets

The analysis uses three public OTT datasets:

- Netflix Titles
- Amazon Prime Titles
- Disney+ Hotstar Titles

Total titles analyzed: **19,925**

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- SQLite
- SQL
- Excel

## Analysis Performed

- Combined three OTT platform datasets
- Compared Movies vs TV Shows
- Analyzed content growth by release year
- Identified the most common genres
- Compared genres across platforms
- Analyzed content ratings
- Performed SQL aggregations using SQLite

## Key Results

### Platform Catalog Size

| Platform | Titles |
|---|---:|
| Amazon Prime | 9,668 |
| Netflix | 8,807 |
| Disney+ Hotstar | 1,450 |

### Movie vs TV Show Mix

- Amazon Prime: 80.82% Movies, 19.18% TV Shows
- Disney+ Hotstar: 72.55% Movies, 27.45% TV Shows
- Netflix: 69.62% Movies, 30.38% TV Shows

### Content Growth

The combined catalog increased from **530 titles in 2012** to **2,159 titles in 2021**.

### Top Genre

**Drama** was the most common genre in the combined analysis.

## Visualizations

1. OTT Content Trend by Release Year
2. Total Titles by OTT Platform
3. Movie vs TV Show Distribution
4. Top 10 Genres Across OTT Platforms
5. Top 5 Genres by OTT Platform
6. Content Ratings Distribution by OTT Platform

## SQL Analysis

SQLite was used to perform:

- Platform-wise title counts
- Platform and content-type aggregation
- Release-year trend analysis
- Genre aggregation
- Platform and content-type analysis with average release year

## Content Strategy Memo

### Insight 1 – Growing OTT Content

OTT content expanded strongly between 2012 and 2021.

**Recommendation:** Continue investing in high-demand content while monitoring changing audience preferences.

### Insight 2 – Different Platform Content Mix

Amazon Prime is more movie-focused, while Netflix has a higher proportion of TV Shows.

**Recommendation:** Platforms can strengthen their weaker content format to create a more balanced catalog.

### Insight 3 – Strong Drama and International Content

Drama and international content are major categories in the analyzed catalogs.

**Recommendation:** Content teams should prioritize successful genres while expanding localized and international content.

## Files

- `Veda_Task31_OTT_Content_Trend_Analysis.ipynb` – Complete Python and SQL analysis
- `OTT_Content_Trend_Analysis.xlsx` – Analysis results
- `netflix_titles.csv` – Netflix dataset
- `amazon_prime_titles.csv` – Amazon Prime dataset
- `disney_plus_titles.csv` – Disney+ Hotstar dataset

## Conclusion

This project demonstrates how Python, SQL, and data visualization can be used to analyze OTT content catalogs and generate actionable insights for content strategy and acquisition decisions.