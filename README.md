# NHANES 2017–2018 Osteoporosis Multiclass Prediction

## Project Overview

This project presents a reproducible statistical and machine learning analysis of osteoporosis status using data from the **National Health and Nutrition Examination Survey (NHANES) 2017–2018**.

The analysis focuses on classifying participants into three osteoporosis status groups — **Normal, Osteopenia, and Osteoporosis** — based on femoral neck bone mineral density (BMD), and evaluating the predictive contribution of clinical and **social determinants of health (SDoH)** factors.

## Analysis

The project includes:

- Definition of osteoporosis status (**Normal / Osteopenia / Osteoporosis**) using femoral neck BMD–derived T-scores
- Data preprocessing and variable preparation
- Descriptive epidemiology and baseline comparisons across osteoporosis groups
- Multiclass prediction modeling
- Model performance evaluation
- Assessment of the predictive contribution of socioeconomic and SDoH factors

## Data

The analysis uses **NHANES 2017–2018** data containing demographic, clinical, socioeconomic, and bone mineral density variables.

The analytic dataset used for this project is provided as:

`NHANES_201718.xlsx`

Variable definitions are documented in:

`NHANES_201718_Variable_Description.docx`

## Repository Contents

- `NHANES_201718.xlsx` — analytic dataset
- `NHANES_201718_Variable_Description.docx` — variable descriptions
- `code.Rmd` — complete reproducible R analysis
- `report.pdf` — final project report

## Software

The analysis was conducted in **R (≥ 4.2.0)**.

All required R packages are loaded within `code.Rmd`.

## Reproducing the Analysis

1. Clone or download this repository.
2. Open `code.Rmd` in RStudio.
3. Set the working directory to the project folder.
4. Click **Knit** to execute the complete analysis.

The R Markdown workflow performs the analysis end-to-end and reproduces the statistical results and model outputs used in the final report.

## Methods

The analysis combines traditional biostatistical methods with multiclass predictive modeling to investigate osteoporosis risk. Particular attention is given to determining whether socioeconomic and SDoH variables provide additional predictive information beyond clinical characteristics.
