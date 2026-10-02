# The World Cup Effect

This project analyzes the 2022 and 2026 FIFA World Cups using SQL, match data, Google Trends, and audience figures.

The goal was to look beyond match results and understand how football interest changed during the World Cup, how 2026 compared with 2022, and whether stronger tournament performance was linked with higher engagement.

### Why I Chose This Project

I wanted to build a SQL project around something I actually follow and enjoy, so I decided to use the FIFA World Cup.

Instead of only looking at scores and winners, I wanted to understand what happens to football interest during the tournament. I was also curious to see whether the 2026 World Cup created more engagement than 2022, and whether teams that performed better also saw a bigger increase in interest.

That led me to combine match data with Google Trends and audience figures and look at the World Cup from both a performance and engagement perspective.

### Dataset Overview

For this project, I used World Cup match data for **2022 and 2026**, along with Google Trends data and published FIFA audience figures.

The match data includes **168 matches in total**:
- 64 matches from 2022
- 104 matches from 2026
- 480 goal records

For the interest analysis, I used weekly Google Trends data for the **Soccer** topic across 13 countries that played in both tournaments:

**Argentina, Belgium, Brazil, Canada, Croatia, France, Mexico, Morocco, Netherlands, Portugal, South Korea, Spain, and USA.**

The combined Google Trends dataset contains **3,237 weekly observations**.

I also used FIFA audience figures to add actual viewership context alongside the search-interest analysis.

**Data sources:** OpenFootball, Google Trends, and FIFA audience reports

### Tools Used

- **PostgreSQL** — data cleaning, transformation, analysis, joins, views, and calculations
- **pgAdmin** — database management and running SQL queries
- **Python** — used only for initial JSON normalization and preparing staging CSV files

 



    













 













    








and excel





 






Only add Excel if you actually used it during this project.
From what we did together, the main workflow was:
Tools used: PostgreSQL, pgAdmin, Python
- PostgreSQL / pgAdmin — cleaning, modeling, queries, analysis
- Python — initial JSON normalization and combining/preparing some CSV data
- Excel — not really part of the analysis unless you personally used it to inspect, organize, or edit the CSV files
So I would not add Excel just to make the tools list longer. It’s better for the README to be accurate.
