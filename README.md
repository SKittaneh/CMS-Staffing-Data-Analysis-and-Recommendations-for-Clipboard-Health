# CMS Staffing Data Analysis for Clipboard Health

This project analyzes nursing home staffing data from the **CMS Payroll Based Journal (PBJ) 2024Q1** dataset to provide actionable recommendations for **Clipboard Health**, a nationwide staffing platform. The project focuses on understanding contractor reliance and staffing efficiency in nursing homes across the U.S. This project was originally implemented in Databricks and PySpark, and was converted to ipynb for uploading to github.

## Project Overview

This project aims to analyze **CMS PBJ** data to uncover staffing patterns and provide recommendations to **Clipboard Health's sales team**. The focus is on understanding:
- **Contractor Utilization Rate**: Nursing homes' reliance on contractors vs. employees.
- **Hours per Resident per Day (HPRD)**: Efficiency metrics comparing contractor and employee performance in terms of care time per resident.

## Data

The dataset includes:
- Daily staffing data for nursing homes in the U.S. (Q1 2024).
- Fields include staff types (RN, LPN, CNA, etc.), hours worked, and resident census.

## Metrics and Analysis

### Contractor Utilization Rate
A key metric that measures the proportion of hours worked by contractors relative to total hours worked by all staff.

Contractor Utilization Rate = (Total Contractor Hours) / (Total Hours)


### Hours per Resident per Day (HPRD)
This metric evaluates the average time contractors and employees spend per resident, useful for assessing efficiency.

HPRD = (Total Hours) / (Resident Census)

HPRD (Contractors) = Total Contractor Hours / Resident Census (MDS)

HPRD (Employees) = Total Employee Hours / Resident Census (MDS)


## Recommendations

1. **Focus on High Contractor Utilization Nursing Homes**:  
   Target nursing homes with higher-than-average contractor reliance for tailored staffing solutions. These homes show greater demand for flexible staffing models.
   
2. **Optimize Care Efficiency Metrics**:  
   Use HPRD metrics to identify homes where contractor care time is significantly lower or higher than employee care time, suggesting potential staffing efficiency improvements.
