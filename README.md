# NYPD Shooting Incident Data Analysis

This project analyzes real-world shooting incident data reported by the NYPD. Using R and data from NYC Open Data, it explores geographic, demographic, and temporal trends to understand where and how gun violence occurs in New York City.

---

## Dataset

- **Source:** [NYC Open Data – NYPD Shooting Incidents](https://data.cityofnewyork.us/api/views/833y-fsy8/rows.csv?accessType=DOWNLOAD)  
- **Columns Used:** Date, time, borough, precinct, perpetrator/victim age, sex, race, murder flag

---

## Tools & Technologies

- **Language:** R  
- **Libraries:** `tidyverse`, `ggplot2`, `lessR`, `lubridate`, `dplyr`  
- **Environment:** RStudio, R Markdown

---

## Analysis Overview

- Selected and cleaned relevant features from raw CSV
- Converted variables to factors and dates
- Visualized borough-level incident counts
- Summarized victim and perpetrator demographics

---

## Key Insights

- **Brooklyn** reported the highest number of shooting incidents
- **Staten Island** had the lowest incident count
- Demographics show most incidents involve male perpetrators and victims

More analysis can be added such as:
- Monthly/yearly trend over time
- Crosstabs of age, race, borough
- Map of incident locations using `leaflet`

---

## How to Run

1. Clone this repo  
2. Open `NYPD_Shooting_Incident.Rmd` in **RStudio**  
3. Install required packages if needed  
4. Knit to HTML or PDF to see the full report  

---

## Author

**Erica Kim**  
Master’s in Data Science – University of Colorado Boulder  
[GitHub Profile](https://github.com/kimerica)
