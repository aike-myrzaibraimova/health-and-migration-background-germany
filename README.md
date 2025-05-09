# Health and Migration Background Analysis in Germany
This R project explores how migration background is related to self-rated health using SOEP (Socio-Economic Panel) data from Germany. It includes data cleaning, merging, visualizations, and simple descriptive statistics.

## Files Included

- `Health_and_Migration_Background.Rmd` – The main R Markdown file with full code and explanations
- `Health_and_Migration_Background.html` – A knitted report to view the results without running the code
- `README.md` – This file

## Project Overview

- **Topic**: Migration background and self-rated health
- **Tools**: R, dplyr, ggplot2
- **Data Source**: SOEP-Core data (`pl.dta`, `ppathl.dta`)
- **Methods**: Data selection, merging, cleaning, factor transformation, and plotting

## Data Notice

> he datasets used in this analysis are **not included** in this repository due to licensing restrictions.  
> You can request access from the official SOEP website at [https://paneldata.org/soep-core](https://paneldata.org/soep-core)

## How to Reproduce the Analysis

1. Download the SOEP datasets `pl.dta` and `ppathl.dta` from [paneldata.org](https://paneldata.org)
2. Place them in a folder called `/data` within your project directory
3. Open `Health_and_Migration_Background.Rmd` in RStudio
4. Install required packages (see below)
5. Knit the R Markdown file or run it chunk by chunk

## Required R Packages

```r
install.packages(c("tidyverse", "haven", "ggplot2", "knitr", "kableExtra"))
