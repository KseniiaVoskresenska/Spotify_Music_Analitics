
Interactive Power BI dashboard and ETL pipeline analyzing Spotify music data
Spotify Music Analytics (Power BI Project)

In this project, I cleaned and prepared a Spotify dataset to build an interactive dashboard in Power BI. The goal was to look into track popularity, streaming numbers, and artist performance across different genres and record labels.

---

What I Did
Excel
1. Data Cleaning & Excel Preparation
Before importing the dataset into Power BI, I worked on the raw data in Excel:
Added a release_year column using the =YEAR() function to extract the release year from date values.
 Created a popularity_rank column using nested IF statements (3 levels) to rank songs based on their performance metrics.
 Filtered out and deleted empty/blank rows to keep the data clean.

2.Power Query (ETL & Data Types)
When I loaded the data into Power BI, I hit a locale formatting issue:
 My dataset used dots (.) for decimal numbers instead of commas. Power Query originally misidentified these numeric columns as text. I fixed this by updating the column locales/region settings so the decimals were parsed correctly.
Verified and set appropriate data types (Integer, Text, Date, Decimal) for all attributes to ensure accurate aggregations.

 3.Power BI Dashboard & Visuals
 Built an interactive dashboard matching Spotify's visual style.
 Added KPI cards for key metrics (total streams, unique artists, total tracks, average popularity score).
 Included interactive slicers for genre, release year, and label filtering.
 Visualized streaming trends over time, label distributions (treemap), and geographical data on a map.

