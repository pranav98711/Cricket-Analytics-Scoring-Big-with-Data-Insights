# **Cricket-Analytics-Scoring-Big-with-Data-Insights**


![](https://github.com/pranav98711/Cricket-Analytics-Scoring-Big-with-Data-Insights/blob/main/GIF%20Files/project1.gif)
![](https://github.com/pranav98711/Cricket-Analytics-Scoring-Big-with-Data-Insights/blob/main/GIF%20Files/part2.gif)
![](https://github.com/pranav98711/Cricket-Analytics-Scoring-Big-with-Data-Insights/blob/main/GIF%20Files/part3.gif)


---

**Project Summary:**

This project revolves around the exciting world of T20 Cricket, specifically the T20 Cricket World Cup, which concluded recently with England emerging as the champions against Pakistan. Our journey began by delving into the world of cricket data analytics, focusing on the T20 World Cup data.

**Key Features:**

**Challenging the Norms:** The project posed a unique challenge - crafting a cricket team with the capability to consistently score 180 runs while defending against the relentless pursuit of 150 runs by formidable opponents. This challenge drove the fusion of strategy and data analytics.

**Data Unearthed:** The journey commenced with scraping crucial data from ESPNcricinfo, sourcing insights from the T20 World Cup 2022. I harnessed BrightData to scrape data from the website in a structured JSON format. A snapshot of this JSON data can be seen below:

![](https://github.com/pranav98711/Cricket-Analytics-Scoring-Big-with-Data-Insights/blob/main/GIF%20Files/T20_Json_Snapshot.png)

**Data Refinement:** Transforming raw JSON data into a structured tabular format was a necessity. Post-transformation, I meticulously cleaned and preprocessed the data using Pandas, ensuring it was primed for in-depth analysis.

![](https://github.com/pranav98711/Cricket-Analytics-Scoring-Big-with-Data-Insights/blob/main/GIF%20Files/T20_CSV_Snapshot.png)

**Power BI Dashboards:** I harnessed the capabilities of PowerBI for data visualization. Loading CSV data into PowerBI, employed Power Query for further data refinement. Creating relationships between various data sources, based on matching columns like Name and MatchID, was instrumental in ensuring data cohesiveness. DAX played a pivotal role in creating new columns, conducting intricate calculations, sorting data, and adapting data types.

**Player Role Definition:** A significant aspect of the project was defining the specific roles and criteria for player positions within the cricket team. Roles including openers, power hitters, middle-order anchors, finishers, all-rounders, and specialist fast bowlers were meticulously defined, finely tuned based on metrics such as batting average, strike rate, and boundary-hitting prowess.

**Interactive Dashboards:**
- **Project Sporton:** Dive into the dynamic world of visualizations, focusing on the batting performance of opener batsmen and power hitters, complemented by insights into their historical performance. Hover over a player's row for detailed batting performance metrics.

- **New Anchors / Middle Order:** This dashboard provides intriguing insights into the batting performance of New Anchors and Middle Order Batsmen, alongside historical match performance metrics. Hover over any player's row to reveal player-specific insights.

- **New Finisher / Lower Order Anchor:** Similar to the previous dashboard, this section explores the performance of finisher batsmen, offering interactive metrics for deeper understanding.

- **New All Rounders / Lower Middle Order:** Gain a comprehensive view of all-rounders, both in terms of batting and bowling performance, to appreciate their versatile abilities.

- **New Specialist Fast Bowlers / Tail End:** This dashboard is dedicated to the prowess of fast bowlers, showcasing their impact through visualizations of their bowling performance.

- **Final11:** The pinnacle of our project, this dashboard serves as the arena for selecting the ultimate team, thoughtfully chosen to take on highly skilled opponents. Furthermore, it provides a summarized overview of the selected players' batting and bowling performance metrics.

Our project's crowning achievement lies in the creation of captivating and informative Power BI dashboards, providing powerful visualization tools for a deeper understanding of T20 Cricket.

With great pride, we showcase our expertise in data scraping, data cleaning, data transformation, and data visualization using Power BI. Join us in unraveling the strategic dynamics of T20 Cricket through data-driven insights and the art of team selection.
