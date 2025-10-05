# Rainfall in Seattle, WA vs Portland, ME

## Project Overview
This project analyzes whether it rains more in **Seattle, WA** or **Portland, ME**.  
It uses daily precipitation data from **January 1, 2018** through **December 31, 2022**.  

**Key finding:** It rains more in Portland, ME than in Seattle, WA.

---

## Data
Precipitation data was sourced from the  
**National Centers for Environmental Information (NOAA Climate Data Tool):**  
[https://www.ncei.noaa.gov/cdo-web/search?datasetid=GHCND](https://www.ncei.noaa.gov/cdo-web/search?datasetid=GHCND)

---

## Analysis
The data was cleaned and prepared as follows:
- Removed all columns except **date** and **precipitation**
- Removed entries with **null** values  
- Dropped **duplicate** or **non-numeric** entries  
- Removed entries **outside** the 2018–2022 time frame  

The analysis included:
- Descriptive statistics (mean, standard deviation, percentiles, min/max)  
- Box plot of average rainfall by month  
- Bar graph of average rainfall by month  
- Bar graph of the proportion of days that received precipitation by month  

---
## Authors
Caroline Buske

---

## Results
- **Portland, ME** experiences more total rainfall than **Seattle, WA**  
- **Seattle** has a higher **proportion of rainy days**  
- **Portland** shows greater variation in rainfall, with large outliers that can skew the mean

---

## License
- This project is licensed under the MIT License
