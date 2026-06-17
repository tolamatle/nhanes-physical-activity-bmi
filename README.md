# Physical Activity and BMI in NHANES 2011–2012

## Overview

This project examines the relationship between objectively measured physical activity and body mass index (BMI) using data from the National Health and Nutrition Examination Survey (NHANES) 2011–2012.

Physical activity was measured using Monitor-Independent Movement Summary (MIMS) units derived from wrist accelerometer data. Statistical analyses were conducted in R and results were presented using a reproducible Quarto report.

## Research Question

Is greater daily movement associated with lower BMI among U.S. participants aged 2–85 years?

## Data Sources

* NHANES 2011–2012 Physical Activity Monitor Data (PAXDAY_G)
* NHANES 2011–2012 Body Measures Data (BMX_G)
* NHANES 2011–2012 Demographic Data (DEMO_G)

Data were obtained from the Centers for Disease Control and Prevention (CDC) NHANES program.

## Methods

* Merged physical activity, demographic, and anthropometric datasets using participant identifier (SEQN)
* Calculated average daily MIMS values
* Removed implausible or missing observations
* Conducted descriptive analyses
* Created visualizations using ggplot2
* Fit multivariable linear regression models predicting BMI

## Key Findings

Higher daily movement was associated with lower BMI after adjustment for age, gender, and race/ethnicity.

A 10,000-unit increase in MIMS was associated with an approximate 2.4-unit decrease in BMI.

## Software Used

* R
* Quarto
* dplyr
* ggplot2
* broom
* gt

## Author

Evelyn Ariceaga, MPH
