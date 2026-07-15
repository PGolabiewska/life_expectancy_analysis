# Life Expectancy Analysis

Visualization project exploring life expectancy from year 2000-2015 for 193 countries. For the analysis, we will consider factors such as alcohol, medical conditions, and BMI.

## Problem Statement

- How life expectancy has changed over the years
- Does Life Expectancy has positive or negative correlation with eating habits, lifestyle, exercise, smoking, drinking alcohol etc.
- What is the impact of schooling on the lifespan of humans?
- Do densely populated countries tend to have lower life expectancy?

## Dataset

- **Source**: [Life Expectancy (WHO)] (life_expectancy_data.csv)
- **2938 rows x 22 columns**: Country,Year,Status,Life expectancy ,Adult Mortality,infant deaths,Alcohol,percentage expenditure,Hepatitis B,Measles , BMI ,under-five deaths ,Polio,Total expenditure,Diphtheria , HIV/AIDS,GDP,Population, thinness  1-19 years, thinness 5-9 years,Income composition of resources,Schooling


## Project Structure
```
Life Expectancy Analysis/
├── basic_data.ipynb        # Overview: structure, missing, body-metric distributions
├── analysis.ipynb   # Medal nations, female participation trend, height trend, top sports
├── README.md
└── data/life_expectancy_data.csv
```

## Tech Stack
- pandas, numpy, matplotlib

## To Do:
- finish Problem Statement
- for removed duplicates take mean value of all duplicated records (eg. deaths/alcohol)
