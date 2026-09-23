# Animal Shelter Power BI

An interactive Power BI project built with Austin Animal Center data to explore animal intakes, outcomes, shelter stay duration, breed patterns, age groups, and yearly trends.

## Project Overview

The goal of this project was to turn shelter records into a clear and visually engaging Power BI report rather than a standard corporate-style dashboard.

The report includes dedicated pages for:

- Overview
- Animals
- Outcomes
- Stay Analysis
- Austin

Interactive filters make it possible to explore the data by animal type, outcome, age group, and year.

## Key Insights

- **Adoption was the most common outcome**, with 33,594 records.
- **Stray animals were the largest intake group**, with 55,935 records.
- The **average shelter stay was 16.8 days**, while the median was about **5 days**, showing the impact of longer-stay cases on the overall average.
- Dogs and cats made up most of the shelter records, with **45,366 dog records** and **29,539 cat records**.

## Dashboard Features

- KPI cards for key shelter metrics
- Breed and age-group analysis
- Outcome analysis by animal type
- Shelter stay analysis
- Yearly intake and outcome trends
- Interactive slicers and cross-filtering
- Custom visual styling with a warm, human-centered shelter theme

## Tools Used

- **Power BI**
- **Power Query**
- **DAX**

## Dataset

The analysis is based on Austin Animal Center intake and outcome data covering **2013–2018**.

Main analytical file:

`aac_intakes_outcomes.csv`

The joined dataset contains **79,672 linked shelter records**.

## Repository Structure

```text
Animal-Shelter-PowerBI/
│
├── Austin_Animal_Center.Report/
├── Austin_Animal_Center.SemanticModel/
├── .gitignore
├── aac_intakes_outcomes.csv
├── austin animal shelter.pbip
├── dashboard-preview.png
└── README.md
```

The `.pbip` file references the report and semantic model folders, so both folders are required for the project to open correctly in Power BI Desktop.

## Dashboard Preview

The dashboard uses a soft cream background, dark green navigation, warm accent colors, and a minimal layout designed to keep the report readable while still visually distinctive.

---

Created as part of my Data Analytics portfolio.
