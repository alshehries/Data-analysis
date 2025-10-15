# Radiation Trend Analysis – Daily Environmental Monitoring (August 2024)

### Project Overview
This project analyzes **daily radiation readings** collected over **31 consecutive days** during August 2024.  
The goal was to examine **daily variability**, test for **normality**, assess **trends**, and determine whether radiation levels showed a **significant increase or decrease** over time.

### Data Summary
- **Data Source:** Open environmental radiation dataset (public data).  
- **Observation Period:** 1–31 August 2024  
- **Variables:**  
  - Total daily reads  
  - Highest read per day  
  - Lowest read per day  
  - Average daily read  

### Methodology
1. **Data Preparation:**  
   - Checked for missing values (none found).  
   - Computed descriptive statistics for all daily measures.  

2. **Normality Testing:**  
   - Used *Kolmogorov–Smirnov* and *Shapiro–Wilk* tests.  
   - Results indicated that most variables were **non-normally distributed** (p < 0.001).  

3. **Correlation Analysis:**  
   - Applied *Spearman’s rank-order correlation* to assess monotonic trends between **dates** and **total reads**.  

4. **Trend Evaluation:**  
   - Visualized daily readings using histograms and line graphs.  
   - Observed slight fluctuations: an early dip, a mid-period rise, and a gradual decline.  

### Key Findings
| Measure | Result | Interpretation |
|----------|---------|----------------|
| Spearman’s ρ | 0.310 | Weak positive monotonic trend |
| p-value | 0.089 | Not statistically significant (α = 0.05) |
| Range | 14,900 – 16,150 | Stable radiation levels |
| Trend Summary | Fluctuating but stable | No clear upward or downward shift |

## Radiation Graphs

![Highest Read](images/Highest_read.png)
![Lowest Read](images/Lowest_read.png)
![Total Reads](images/Total_reads.png)
![Reads Average](images/Reads_average.png)
![Line Graph](images/Line_graph.png)

> **Conclusion:**  
> Radiation readings fluctuated slightly across the month but remained within a narrow, stable range.  
> While a weak positive trend was detected, it was **not statistically significant**, suggesting **no clear evidence of an overall increase or decrease** in radiation levels during the study period.

###  Tools & Techniques
- **Software:** SPSS v29, Excel 2021  
- **Statistical Tests:** Descriptive analysis, Kolmogorov–Smirnov, Shapiro–Wilk, Spearman correlation  
- **Visualization:** Histograms, line charts, trend line plots  

###  Future Work
- Extend the observation period to several months to enhance statistical power.  
- Include external factors (e.g., temperature, humidity, or wind) to explore environmental correlations.  
- Apply time series models (ARIMA or exponential smoothing) for predictive analysis.  

### Keywords
`Radiation` · `Environmental Data` · `SPSS` · `Trend Analysis` · `Spearman Correlation` · `Time Series` · `Nonparametric Statistics` · `Data Visualization`
