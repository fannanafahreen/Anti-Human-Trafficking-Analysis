## Overview
This dashboard was built as part of a data science 
internship focused on anti-human trafficking efforts. 
It uses official UNODC (United Nations Office on Drugs 
and Crime) data to visualise global trafficking patterns 
across 160 countries from 2003 to 2022.

## What the Dashboard Shows
- Total detected trafficking victims worldwide
- Victim breakdown by gender (Female, Male, Other, Unknown)
- Victim breakdown by age (Children vs Adults)
- Exploitation type trends over time 
  (Forced Labour vs Sexual Exploitation)
- Top trafficking countries
- Victim records by reporting dimension

## Key Findings
- Sexual exploitation accounts for 58% of detected victims
- Female victims make up the majority at 505K
- Child victims account for 274K of total cases
- Detected cases have increased significantly since 2003

## Dataset
- Source: UNODC Global Report on Trafficking in Persons
- Link: dataunodc.un.org/dp-trafficking-persons
- Years: 2003-2022
- Countries: 160+

## Tools Used
- Python (Pandas) — data cleaning
- Jupyter Notebook — data exploration  
- Power BI Desktop — visualisation

## Data Cleaning Steps
- Replaced suppressed values (<5) with 2
- Converted txtVALUE column to numeric
- Fixed Year column to integer format
- Retained all dimensions for flexible filtering
