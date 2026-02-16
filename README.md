# FRENCH ROAD ACCIDENT ANALYSIS (2021)

Statistical modeling of road accident severity and frequency in France based on ONISR data.

![R](https://img.shields.io/badge/Language-R-blue)
![Analysis](https://img.shields.io/badge/Analysis-GLM%20%26%20Clustering-orange)
![Report](https://img.shields.io/badge/Report-LaTeX-green)

## OVERVIEW
This project applies advanced statistical methods to analyze road safety data from 2021. The goal is to identify risk factors and model accident occurrences using three complementary approaches:

1. Linear Regression: Modeling the severity score of accidents based on location, vehicle type, and user characteristics.
2. Unsupervised Learning (Clustering): Identifying typical accident profiles and typologies.
3. Frequency Modeling: Analyzing accident counts at departmental and regional scales using Poisson and Negative Binomial regression (with population and traffic offsets).

## PROJECT STRUCTURE

- data/ : Raw datasets (ONISR 2021, INSEE, TMJA)
- Regression_lineaire/ : Severity score modeling (RMarkdown & PDF)
- clustering/ : K-Means/HCA implementation to find profiles
- frequence/ : Count data modeling (Poisson/NegBin)
- rapport/ : Final detailed report (LaTeX source & PDF)
- Figures/ : Generated plots and graphs

## METHODOLOGY & RESULTS

### 1. Linear Regression (Severity)
Objective: Construct a severity score and explain it using explanatory variables.
File: Regression_lineaire/reg_lineaire2.pdf

### 2. Clustering (Typology)
Objective: Group accidents by similarity to detect patterns.
Method: Data preparation and partitioning.
File: clustering/clustering.pdf

### 3. Frequency Modeling (Risk Factors)
Objective: Model the number of accidents independently of traffic volume.
Approaches:
- Generalist: Country-wide scale (Offset: Population).
- Precision: Regional scale (Auvergne-Rhône-Alpes) using TMJA (Annual Average Daily Traffic) as offset.
File: Frequence/Frequence.pdf

## GETTING STARTED

To reproduce the analysis, you will need R and RStudio.

1. Clone the repository:
   git clone https://github.com/KylianAnaclet/road-safety-modeling-france.git

2. Data Setup:
   Unzip the file 'ONISR-2021.csv.zip' located inside the 'data/' folder.

3. Run Analysis:
   Open any .Rmd file in RStudio and click "Knit" to generate the reports.

## AUTHORS
Project realized for the Applied Mathematics curriculum.

- Kylian Anaclet
- Ilyes Kebairi
- Muhamad Zaiinizee Bin Davin
- Younes Chennouf
