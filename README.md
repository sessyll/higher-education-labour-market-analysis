# Higher Education and the Labour Market in the Netherlands (2013–2025)

An end-to-end data analytics project exploring long-term labour market outcomes across educational levels in the Netherlands using official CBS Open Data.

**Tools:** Python • PostgreSQL • SQL • Docker • Tableau

🔗 **Interactive Tableau Story:** *https://public.tableau.com/authoring/EducationLevel-LabourMarket/Story1#1
*

---

## Project Overview

This project analyses labour market developments across educational levels in the Netherlands over a twelve-year period (2013–2025).

Starting from raw CBS Open Data, I designed and implemented a complete analytical workflow that included data preparation in Python, validation in PostgreSQL using SQL, and interactive dashboard development in Tableau.

Particular emphasis was placed on metadata interpretation and validation of official labour market indicators before visualisation, ensuring that analytical findings accurately reflected the underlying data.

---

## Objectives

The project was developed to answer the following questions:

- How have labour market outcomes evolved across educational levels?
- How has self-employment changed over time?
- How has the distribution of full-time and part-time employment evolved?
- How have unemployment trends differed between educational groups?

---

## Data Source

**Provider:** Statistics Netherlands (CBS Open Data)

**Dataset:** 85266NED

**Study Period:** 2013–2025

---

## Analytics Workflow

```text
CBS Open Data
        ↓
Python Data Cleaning
        ↓
PostgreSQL Database
        ↓
SQL Validation
        ↓
Validated Dataset
        ↓
Interactive Tableau Story
```

---

## Dashboard Overview

The Tableau Story presents three complementary analytical perspectives:

### Self-Employment

Shows how the educational composition of the self-employed population evolved over time.

### Employment Type

Compares the educational distribution of full-time and part-time employment across educational groups.

### Unemployment

Analyses long-term unemployment trends across educational levels using official CBS unemployment rates.

---

## Key Findings

- Higher education groups consistently represented the largest share of the self-employed population.
- The educational composition of both full-time and part-time employment gradually shifted towards higher education groups.
- Unemployment declined substantially across all education levels after 2015, while higher education groups consistently maintained the lowest unemployment rates.

---

## Skills Demonstrated

- Data Cleaning
- Data Transformation
- Python (Pandas)
- SQL
- PostgreSQL
- Metadata Interpretation
- Data Validation
- Tableau
- Dashboard Storytelling
- Trend Analysis

---

## Repository Structure

```
higher-education-labour-market-analysis
│
├── README.md
├── case-study.pdf
├── screenshots
├── python
├── sql
└── tableau
```

---

## Author

**Selen Apaydin-Kasap**

Data Analytics Portfolio
