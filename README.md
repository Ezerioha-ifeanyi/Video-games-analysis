# 🎮 Video Game Sales Analysis Dashboard

### An Interactive Power BI Analysis of Video Game Sales, Genres, Publishers, Consoles and Regional Performance

## 1. Project Overview

The video game industry has experienced significant changes over the years, with shifts in consumer preferences, gaming platforms, genres, publishers, and regional markets.

For this project, I developed an interactive **Power BI dashboard** to analyze video game sales data and uncover patterns in:

* Overall game sales performance
* Sales trends across release years
* Most successful video game genres
* Leading publishers by total sales
* Top-performing individual titles
* Console/platform popularity
* Regional sales performance
* Differences between Japanese and North American markets

The objective was to transform raw video game sales data into an **interactive analytical tool** that could help users quickly understand what types of games, publishers, platforms, and periods have historically generated the most sales.

---

# 2. The Business Question

Rather than simply asking *“How many video games were sold?”*, I approached the dataset from several analytical perspectives.

The key questions guiding the analysis were:

### Market performance

* How have video game sales changed over time?
* When did the industry experience its strongest sales period?
* Are there identifiable periods of rapid growth or decline?

### Genre performance

* Which genres generate the highest total sales?
* How do popular genres compare with one another?

### Publisher performance

* Which publishers dominate the market?
* How concentrated are sales among the leading publishers?

### Product performance

* Which individual game titles generated the highest sales?
* Do blockbuster titles significantly outperform the rest of the market?

### Regional performance

* How do Japanese and North American sales compare over time?
* How does North American performance vary among major publishers?

### Platform analysis

* Which gaming console/platform appears most frequently in the dataset?

---

# 3. Data Analysis Approach

I used **Microsoft Power BI** to transform the raw dataset into an interactive analytical dashboard.

The workflow involved several stages:

### Data preparation

* Imported the video game sales dataset into Power BI.
* Reviewed the available fields and data types.
* Prepared the data for analysis.
* Ensured sales-related fields could be aggregated appropriately.
* Structured categorical variables such as genre, console, publisher and release year for visualization.

### Data modelling and calculations

I created analytical measures to support the dashboard, including metrics for:

* Total sales
* Average sales
* Median sales
* Sales range
* Sales by release year
* Sales by genre
* Sales by publisher
* Sales by title
* Regional sales
* Publisher-level regional ratios

This allowed the dashboard to move beyond displaying raw records and instead provide **aggregated business insights**.

### Dashboard development

I then designed the dashboard around several analytical layers:

**KPI layer → Market trends → Publisher analysis → Genre analysis → Regional analysis → Product analysis**

This structure allows a recruiter or stakeholder to move from a high-level overview into specific areas of the market.

---

# 4. Dashboard Design

The dashboard was designed to answer the most important questions within a single screen.

The dashboard contains:

### KPI cards

* Sales Range: **$20.32M**
* Average Total Sales: **$115.85K**
* Median Total Sales
* Mode of Genre
* Mode of Console

### Interactive filters

* Developer
* Release date

### Analytical visuals

* Total Sales by Release Year
* NA Region Ratio by Publisher
* Top 5 Publishers by Total Sales
* Top 5 Genres by Total Sales
* Japanese vs North American Sales by Release Year
* Top 10 Titles by Total Sales

The combination of **KPI cards, slicers, line charts, donut charts and horizontal bar charts** makes the dashboard useful for both exploratory analysis and executive-level reporting.

---

# 5. Key Findings

## 5.1 Video game sales experienced a major growth period

One of the clearest patterns in the analysis is the substantial growth in total video game sales from the late 1990s into the 2000s.

The **Total Sales by Release Year** visualization shows relatively low sales during the earlier years, followed by a significant acceleration around the late 1990s and early 2000s.

Sales continued increasing into the mid-to-late 2000s, reaching a peak of approximately **$0.5 billion in annual total sales** around the late 2000s.

After this peak, sales declined considerably toward the late 2010s.

### What this suggests

The industry appears to have gone through a period of rapid expansion before experiencing a substantial decline in recorded sales in the later years represented in the dataset.

This trend could potentially reflect several factors, including:

* Changes in gaming platforms
* Evolution of digital distribution
* Changes in consumer purchasing behaviour
* Dataset coverage and completeness
* Increasing importance of newer forms of gaming not represented equally in the historical data

This is an important example of why **trend analysis should be interpreted alongside data coverage and business context rather than treated as a simple cause-and-effect relationship.**

---

# 5.2 Sports is the highest-selling genre

The genre analysis shows a clear hierarchy among the leading genres.

| Rank | Genre       |    Total Sales |
| ---- | ----------- | -------------: |
| 1    | **Sports**  | **$1,186.77M** |
| 2    | **Action**  | **$1,124.95M** |
| 3    | **Shooter** |   **$995.47M** |
| 4    | **Misc**    |   **$557.55M** |
| 5    | **Racing**  |   **$523.51M** |

**Sports** is the highest-performing genre, generating approximately **$1.19 billion** in total sales.

Action follows closely at approximately **$1.12 billion**, while Shooter games generated approximately **$995 million**.

### Key insight

The top three genres alone account for a substantial proportion of the sales represented in the dataset.

This indicates that the market is not evenly distributed across genres. Instead, certain categories—particularly **Sports, Action and Shooter**—have historically generated considerably higher sales.

For a publisher or game developer, this could indicate that these genres have historically offered significant commercial opportunities, although genre popularity alone would not guarantee the success of an individual title.

---

# 5.3 Sales are concentrated among major publishers

The publisher analysis reveals a strong concentration of sales among a relatively small group of companies.

The top five publishers are:

| Rank | Publisher           |  Total Sales |
| ---- | ------------------- | -----------: |
| 1    | **Activision**      | **$722.77M** |
| 2    | **Electronic Arts** | **$644.13M** |
| 3    | **EA Sports**       | **$485.66M** |
| 4    | **Ubisoft**         | **$462.57M** |
| 5    | **THQ**             | **$320.89M** |

Activision leads the group with approximately **$722.77 million** in total sales.

Electronic Arts follows with approximately **$644.13 million**.

### Key insight

The difference between the top publishers is significant, but the leading publishers still operate at a much higher sales scale than the fifth-ranked publisher.

This demonstrates how publisher performance can be investigated not only through individual titles but also through **portfolio-level sales aggregation**.

---

# 5.4 Blockbuster titles dominate the top of the market

The Top 10 Titles visualization provides another important perspective.

The highest-selling title in the dashboard is:

### 🥇 Grand Theft Auto V

**$64.29M**

This is followed by several highly successful **Call of Duty** titles, including:

* Call of Duty: Black Ops — approximately **$30.99M**
* Call of Duty: Modern Warfare — approximately **$30.71M**
* Call of Duty: Black Ops — approximately **$29.59M**
* Call of Duty: Ghosts — approximately **$28.80M**
* Other Call of Duty titles also appear among the top performers.

Minecraft and Grand Theft Auto IV also appear among the highest-selling titles.

### Key insight

The top-performing titles demonstrate the commercial impact of established franchises.

The presence of multiple **Call of Duty** titles in the top 10 suggests that franchise strength can play an important role in producing repeated high-performing releases.

Meanwhile, the exceptional performance of Grand Theft Auto V shows how a single blockbuster can significantly outperform many other titles in the market.

---

# 5.5 Japanese and North American markets show different sales patterns

The dashboard compares **Japanese Sales** and **North American Sales** across release years.

The difference between the two markets becomes particularly pronounced during the industry's strongest growth period.

North American sales rise substantially during the 2000s, reaching a peak of roughly **$0.3 billion** in the visualization.

Japanese sales remain considerably lower throughout much of this period.

### Key insight

The two markets do not exhibit identical purchasing patterns.

North America appears to have been a considerably larger sales market within this dataset, particularly during the industry's peak years.

This highlights the importance of **regional segmentation** when evaluating video game performance.

A game that performs strongly in one geographic market may not necessarily achieve the same level of performance elsewhere.

---

# 5.6 Publisher-level regional performance

The **NA Region Ratio by Publisher** visualization provides another layer of analysis by examining the North American contribution across selected publishers.

The displayed ratios are approximately:

* **Activision — 0.586**
* **EA Sports — 0.550**
* **Electronic Arts — 0.500**

These figures indicate that North American sales represent a substantial share of the regional sales composition for the publishers displayed.

### Analytical value

This visualization moves the analysis beyond simply asking:

> *“Who sells the most?”*

and towards:

> *“Where are these publishers generating their sales?”*

That distinction is important because overall sales performance and geographical sales concentration can tell different stories.

---

# 5.7 The dashboard reveals the importance of time

One of the strongest analytical themes across the dashboard is **time**.

The release-year trend and regional comparison both show that sales behaviour changes substantially across different periods.

The market was relatively small in the early years represented, expanded rapidly around the turn of the millennium, reached its strongest performance during the 2000s, and subsequently declined in the later years shown.

This makes **release year one of the most important dimensions for understanding the dataset**.

---

# 6. An Interesting Data Quality Observation

One particularly interesting aspect of the dashboard is the **median total sales value of $0**.

Rather than ignoring this result, I would actually mention it in your portfolio as an example of analytical awareness.

A median of zero suggests that a large portion of the underlying records may have zero or missing recorded sales values, depending on how the dataset represents missing observations.

This has an important implication:

> **The average sales value of $115.85K should not be interpreted without considering the distribution of the underlying data.**

This is precisely why I would recommend that, in the final version of your portfolio, you explain how missing/zero sales values were treated during data cleaning.

That demonstrates something recruiters value highly: **you don't just build visuals—you question what the numbers mean.**

---

# 7. Interactive Analysis

A major strength of the dashboard is that it is not a static report.

The inclusion of **Developer** and **Release Date** slicers allows users to dynamically investigate different parts of the dataset.

For example, a user could select:

> **A specific developer → a specific period → observe changes in genre, publisher, regional and title performance.**

This transforms the dashboard from a presentation tool into an **exploratory analytical application**.

The ability to interactively filter multiple visualizations from a single selection demonstrates my understanding of Power BI's interactive reporting capabilities.

---

# 8. Power BI Skills Demonstrated

This project demonstrates several skills relevant to a **Data Analyst / BI Analyst / Power BI Developer** role.

### Data preparation

* Data cleaning
* Data type handling
* Data transformation
* Preparation of categorical and numerical fields

### Data analysis

* Aggregation
* Descriptive statistics
* Trend analysis
* Ranking
* Comparative analysis
* Regional analysis
* Time-series analysis

### Power BI

* Interactive dashboard development
* DAX measures
* KPI cards
* Slicers
* Line charts
* Donut charts
* Bar charts
* Conditional/filter-driven analysis
* Data storytelling
* Dashboard layout and visual hierarchy

### Analytical thinking

Perhaps more importantly, the project demonstrates the ability to move from:

**Raw data → Questions → Measures → Visualizations → Insights → Business story**

rather than simply producing charts.

---

# 9. The Story Behind the Dashboard

If I were presenting this project to a recruiter, I would summarize the story like this:

> **The video game market represented in the dataset experienced substantial growth from the late 1990s, reaching its strongest sales period during the 2000s. This growth was driven heavily by a small number of highly successful genres, publishers and blockbuster franchises. Sports, Action and Shooter emerged as the strongest genres, while Activision and Electronic Arts were among the leading publishers by total sales. At the product level, Grand Theft Auto V significantly outperformed other titles, while multiple Call of Duty releases demonstrated the commercial strength of established franchises. Regional analysis also revealed a considerable difference between North American and Japanese sales, particularly during the market's peak period.**

That is the **story**, rather than simply a description of your charts.

---

# 10. Business Recommendations

Although this is primarily an exploratory analysis rather than a predictive model, several strategic observations can be drawn from the findings.

### 1. Investigate high-performing genres

Sports, Action and Shooter games generated the highest sales in the dataset.

Publishers assessing historical opportunities could investigate the characteristics that contributed to success in these genres.

### 2. Study successful franchises

The strong representation of Call of Duty and Grand Theft Auto titles among the top-selling games suggests that franchise recognition can be an important component of commercial success.

### 3. Consider regional differences

The substantial difference between Japanese and North American sales suggests that publishers should consider regional preferences when developing marketing and distribution strategies.

### 4. Analyse market changes over time

The sharp increase and subsequent decline in recorded sales demonstrates why historical trends should be incorporated into market analysis rather than evaluating titles in isolation.

### 5. Investigate data completeness

The median sales value of zero should prompt further investigation into missing, zero or unreported sales values before using the dataset for forecasting or predictive modelling.

---

# 11. What I Learned From the Project

One of the most important lessons from this project was that **effective data visualization is not about putting as many charts as possible on a page.**

The challenge was to identify the questions that mattered and then select visuals that could answer those questions quickly.

For example:

* **KPI cards** communicate the overall state of the dataset.
* **Line charts** reveal changes over time.
* **Bar charts** make publisher, genre and title rankings easy to compare.
* **The donut chart** provides a quick view of regional composition.
* **Slicers** allow users to investigate the data interactively.

The project also reinforced the importance of validating analytical results. A visually attractive dashboard can still communicate misleading information if the underlying data, measures or assumptions are not properly examined.

---

# 12. Portfolio Project Summary

You can place this shorter version near the top of your portfolio:

### Video Game Sales Analysis | Power BI

**Objective:**
Analyze historical video game sales data to identify trends across genres, publishers, platforms, titles and geographic markets.

**Tools:**
`Power BI | DAX | Data Cleaning | Data Visualization | Exploratory Data Analysis`

**Key findings:**

* Sports was the highest-selling genre at **$1.19B**.
* Activision led the top publishers with **$722.77M** in sales.
* Grand Theft Auto V was the highest-selling title at **$64.29M**.
* North American sales substantially exceeded Japanese sales during the industry's strongest growth period.
* Overall sales increased sharply during the 2000s before declining in the later years represented in the dataset.
* The median sales result highlighted the need to investigate zero/missing sales records before deeper statistical modelling.

**Outcome:**
Developed an interactive Power BI dashboard that transforms raw video game sales records into a concise, filterable view of market trends, publisher performance, genre popularity, regional differences and blockbuster titles.

---

# 13. A Stronger “About This Project” Version for Your Website

If your portfolio has a project-card format, I would use something like this:

> ### Video Game Sales Analysis
>
> **Power BI | DAX | Data Analytics | Data Visualization**
>
> How have video game sales evolved over time, and what separates the industry's most successful genres, publishers and titles?
>
> I explored historical video game sales data using Power BI to answer these questions through an interactive analytical dashboard. The analysis revealed substantial market growth during the 2000s, with Sports, Action and Shooter emerging as the strongest genres. Activision led the publisher rankings with $722.77M in total sales, while Grand Theft Auto V was the highest-selling individual title at $64.29M.
>
> The dashboard also compares Japanese and North American sales over time, investigates publisher-level regional performance and allows users to filter the analysis by developer and release date.
>
> Beyond visualization, the project demonstrates my ability to **translate raw data into meaningful business questions, build analytical measures, identify trends and communicate insights through interactive BI reporting.**

---

## 14. How I Would Structure the Project on Your Portfolio

I recommend presenting the project in this order:

**01 — Project Overview**
What problem were you solving?

↓

**02 — Business Questions**
What did you want to discover?

↓

**03 — Dataset & Preparation**
What data did you use and how did you prepare it?

↓

**04 — Dashboard**
Show the full dashboard screenshot.

↓

**05 — Key Insights**
Use 5–7 major findings with selected visual snippets.

↓

**06 — Interactive Analysis**
Explain the slicers and user interaction.

↓

**07 — Power BI Skills Demonstrated**
DAX, modelling, visualization, filtering, etc.

↓

**08 — Business Recommendations**
What could a publisher/analyst learn from the findings?

↓

**09 — Lessons Learned**
What did the project teach you?

↓

**10 — Project Links**
GitHub / Power BI / documentation.

---

### One important recommendation

For a **recruiter-focused portfolio**, don't make the page overwhelmingly long. The detailed analysis above is useful as your underlying documentation, but the actual portfolio page should be **visually driven**: dashboard → 5–7 insights → methodology → skills → links.

Also, if you can share the **original dataset or your `.pbix`/Power BI project**, I can take this one step further and help you document the **actual data-cleaning process, data model, DAX measures, methodology, challenges, and exact business insights** rather than inferring those parts from the dashboard screenshot.
