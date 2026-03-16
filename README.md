# Mon Départ(ement) — Socio-Economic Analysis of French Departments

A data analysis project exploring the relationship between income levels 
and quality of life across French departments.

## Research question

> Are French departments with the highest average incomes necessarily 
> those offering the best quality of life?

## Key findings

- High average salaries do **not** guarantee better living conditions
- Correlation tests found **no significant relationship** between income 
  level and unemployment/poverty rates
- ANOVA tests showed that average income **does** significantly affect 
  the number of cultural establishments
- Some lower-income departments offer more balanced living conditions 
  (lower density, moderate poverty, good cultural access)

## Data sources

All data from [data.gouv.fr](https://www.data.gouv.fr):
- Income tax data by department (2000–2017)
- Social housing indicators by department
- Cultural establishments by department (2022)

## Database schema

4 relational tables built in SQL:

| Table | Description |
|-------|-------------|
| `Departement` | 101 rows × 13 columns — socio-economic indicators |
| `Region` | 18 rows × 2 columns — region codes and names |
| `Etablissement` | 101 rows × 4 columns — cultural establishments |
| `Logement` | 101 rows × 5 columns — housing indicators |

## Methods

- Exploratory data analysis (EDA)
- Correlation tests (χ² independence test, linear correlation coefficient)
- ANOVA
- Data visualization (maps, charts)

## Tech stack

- **R / R Markdown** — analysis and report
- **SQL (MySQL)** — relational database
- **HTML / CSS / PHP** — interactive web interface
- **data.gouv.fr** — open government data

## Authors

Group project — Licence MIASHS, Université Paul-Valéry Montpellier (2025)  
Team GBSC: Kardiatou BA, Lea CARMINATI, Diella Joannie GATEKA, Lana SCHEMBRI