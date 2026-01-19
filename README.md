# UIDAI Data Hackathon – Aadhaar Analytics & Decision Framework

## Overview
This project analyzes UIDAI-provided Aadhaar enrolment, demographic, and biometric datasets to identify abnormal patterns, temporal trends, and operational risks. The objective is to transform large-scale transactional data into actionable insights that support informed decision-making and system improvement.

## Datasets
- Aadhaar Biometric Data  
- Aadhaar Demographic Update Data  
- Aadhaar Enrolment Data  

Common dimensions include date, state, district, and pincode, with age-bucketed activity metrics.

## Methodology
The analysis follows a structured, multi-phase pipeline:
1. **Data Consolidation & Validation** – Concatenation of dataset shards and schema checks  
2. **Univariate Profiling** – Distribution analysis, long-tail behavior, and normality testing  
3. **Anomaly Detection** – Robust, non-parametric methods (IQR, MAD, percentile thresholds)  
4. **Temporal Trend Analysis** – Rolling medians, trend testing, and change-point detection  
5. **Decision Framework** – State-level risk scoring and categorization (Low / Medium / High)

## Key Insights
- Aadhaar enrolment and biometric activity exhibit heavy-tailed, non-Gaussian behavior  
- Severe anomalies are geographically concentrated and often precede structural shifts  
- Temporal analysis reveals sustained regime changes rather than isolated spikes  
- A risk-based framework enables targeted monitoring and intervention at the state level


## Tools & Libraries
Python, pandas, NumPy, matplotlib, SciPy, scikit-learn



