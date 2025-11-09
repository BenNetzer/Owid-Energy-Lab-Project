# OWID Energy Lab Project

An exploratory R project using the classic OWID Energy dataset.  
Together with **Omri Halevy**, we analyzed global and regional energy trends to see how patterns of production and use have changed over time.

---

## Quick view
**HTML report:**  
[View the full report]([https://BenNetzer.github.io/OWID-Energy-Lab-Project/Lab_1_Halevy_Omri_and_Netzer_Ben.html](https://bennetzer.github.io/Owid-Energy-Lab-Project/))

---

## Files
- `Lab_1_Halevy_Omri_and_Netzer_Ben.html` – final report (best for viewing)
- `Lab_1_Halevy_Omri_and_Netzer_Ben.Rmd` – source R Markdown 
- Additional csv files with our data. 
---

## Reproduce
```r
# R >= 4.2 recommended
install.packages("pacman")
pacman::p_load(tidyverse, ggplot2, dplyr)

# Knit the Rmd to HTML from RStudio (or run:
# rmarkdown::render("Lab_1_Halevy_Omri_and_Netzer_Ben.Rmd"))

---

# Project by Ben Netzer and Omri Halevy
