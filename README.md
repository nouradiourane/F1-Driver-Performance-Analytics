# F1-Driver-Performance-Analytics
An end-to-end Formula 1 driver performance analysis project using Python, SQL, Excel and Power BI (2022–2024).
# 🏎️ Formula 1 Driver Performance Analytics (2022–2024)

### A Business-Driven Data Analytics Project | Python · SQL · Excel · Power BI

---

## 📌 Project Overview

This project analyzes Formula 1 driver and constructor performance across the 2022, 2023 and 2024 seasons.

The objective is to transform raw Formula 1 race and qualifying data into meaningful business insights that help evaluate driver performance, understand competitive effectiveness and identify patterns influencing race outcomes.

Rather than focusing exclusively on championship points and race victories, this analysis explores multiple performance indicators, including consistency, qualifying effectiveness, race results and positions gained or lost.

The final deliverable is an interactive Power BI dashboard designed to communicate findings and support data-driven performance evaluation.

---

## 🎯 1. Business Problem

Formula 1 teams operate in an extremely competitive environment where driver performance plays an important role in achieving championship success.

However, evaluating driver effectiveness using championship points or race victories alone may provide an incomplete picture of overall performance.

Teams need a more comprehensive approach to understand:

- Which drivers consistently deliver strong results?
- Does a strong qualifying position translate into a strong race finish?
- Which drivers demonstrate the greatest ability to gain positions during races?
- Which constructors achieve the strongest competitive performance?

**The central business question:**

How can historical Formula 1 performance data be used to evaluate driver effectiveness, identify competitive trends and support better-informed performance decisions?

---

## 🎯 2. Project Objectives

The main objectives of this analysis are to:

1. Evaluate driver performance across three Formula 1 seasons.
2. Identify the highest-performing drivers based on key performance indicators.
3. Measure driver consistency throughout the selected seasons.
4. Investigate the relationship between qualifying positions and final race positions.
5. Compare constructor performance.
6. Identify drivers who consistently gain or lose positions during races.
7. Translate analytical findings into actionable business recommendations.

---

## 📊 4. Dataset & Scope

The analysis covers three Formula 1 seasons:

- 2022
- 2023
- 2024

The project combines two main datasets:

**Race Results**
- Driver information
- Constructor information
- Starting grid position
- Final race position
- Championship points
- Laps completed
- Race status

**Qualifying Results**
- Qualifying position
- Q1 time
- Q2 time
- Q3 time

### Dataset Overview

| Season | Race Records | Qualifying Records |
|---|---:|---:|
| 2022 | 440 | 440 |
| 2023 | 440 | 440 |
| 2024 | 479 | 479 |
| **Total** | **1,359** | **1,359** |

The combined analytical dataset contains 1,359 driver-race records.

---

## 🛠️ 5. Tools & Technologies

| Tool | Purpose |
|---|---|
| Python | Data collection, preparation and validation |
| SQL | Data querying and analytical calculations |
| Excel | Data inspection and exploration |
| Power BI | KPI visualization and interactive dashboard |

---

## ⚙️ 6. Data Analytics Process

### Step 1 — Data Collection
Collected historical Formula 1 race and qualifying information for the 2022–2024 seasons.

### Step 2 — Data Preparation
Converted the collected data into structured CSV files and prepared them for analysis.

### Step 3 — Data Quality Validation
Performed validation checks to identify missing essential values, duplicate records and invalid qualifying positions.

The qualifying datasets contained no duplicate driver-race records or invalid qualifying positions.

### Step 4 — Data Integration
Combined race and qualifying datasets using three matching identifiers:

- Season
- Race round
- Driver ID

A LEFT JOIN approach ensured that race-result records were preserved during integration.

### Step 5 — Exploratory Data Analysis
Explored driver performance, qualifying effectiveness, race outcomes and constructor performance.

### Step 6 — KPI Development
Developed performance indicators to evaluate drivers and constructors across the selected seasons.

### Step 7 — Dashboard Development
Designed an interactive Power BI dashboard to present the analytical results and communicate key findings.

---

## 📈 7. Key Performance Indicators (KPIs)

The analysis focuses on the following performance indicators:

| KPI | Definition |
|---|---|
| Total Points | Total championship points accumulated |
| Total Wins | Number of first-place race finishes |
| Total Podiums | Number of top-three race finishes |
| Average Finishing Position | Average classified race finishing position |
| Driver Consistency | Variability in finishing positions |
| Positions Gained/Lost | Difference between starting grid and finishing position |
| Qualifying Position | Driver's final qualifying position |

*Note: Average finishing position should be calculated using classified numeric finishing positions. Positions gained/lost require careful treatment of unclassified results. Sprint results are excluded from the main race analysis.*

---

## 🔍 8. Key Findings & Insights

This section presents the main discoveries from the analysis.

The findings will be supported by the Power BI dashboard and calculated KPIs.

**Key areas investigated:**

- Overall driver performance and championship points.
- Driver consistency across the three seasons.
- The relationship between qualifying performance and race outcomes.
- Constructor performance comparisons.
- Race position gains and losses.

*Actual numerical findings and rankings should be added here based on the final analytical results.*

---

## 💡 9. Business Recommendations

The analysis aims to provide insights that can support performance evaluation and strategic decision-making.

Potential recommendations include:

- Evaluate drivers using multiple performance indicators rather than relying exclusively on championship points.
- Monitor consistency to identify drivers who deliver reliable race results.
- Investigate qualifying performance to understand its relationship with final race outcomes.
- Compare starting positions with race finishes to identify opportunities for improving race execution.
- Evaluate constructor performance using both individual driver contributions and overall team results.

---

## 📊 10. Power BI Dashboard

The final dashboard provides an interactive overview of Formula 1 driver and constructor performance.

**Dashboard Preview**

<!-- Add your dashboard screenshot here -->

[F1 Driver Performance Dashboard](Dashboard/dashboard_overview.png)

The dashboard is designed to help users explore performance indicators, compare drivers and identify competitive trends across the 2022–2024 seasons.

**Power BI Report:** 

Explore the interactive Formula 1 Driver Performance Dashboard:

[View the Power BI Dashboard](https://app.powerbi.com/groups/me/reports/1f9de240-e209-4081-99da-8be004169c23/29ba8d40c25bc23add2d?experience=power-bi)

---

## ⚠️ 11
