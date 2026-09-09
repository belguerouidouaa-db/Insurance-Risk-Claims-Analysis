# Insurance Risk & Claims Analysis

> An interactive Power BI analysis of insurance policies and claims, exploring claim patterns across customer demographics, vehicle characteristics, coverage zones, and other risk factors.

`POWER BI` · `DAX` · `DATA VISUALIZATION` · `BUSINESS ANALYTICS`

---

## Project Overview

This project uses **Power BI** to analyze insurance policy and claims data and identify patterns associated with claim activity and customer characteristics.

The dashboard provides an interactive view of **policy volume, total claim amount, claim frequency, and average claim amount**, with additional analysis across car usage, vehicle make and year, age groups, coverage zones, education, marital status, and other customer segments.

---

## Dashboard Preview

<p align="center">
  <img src="assets/insurance-dashboard.png" alt="Insurance Risk and Claims Analysis Dashboard" width="100%">
</p>

---

## Analysis Focus

The dashboard explores:

- Overall **policy and claims KPIs**
- Claim amount by **car use and car make**
- Claim distribution across **coverage zones**
- Claim patterns by **age group**
- Claim amount by **vehicle year**
- Claims based on **number of kids driving**
- Claim distribution by **education and marital status**
- Customer distribution by **gender**
- Interactive measure selection for exploring different metrics

---

## Key Insights & Business Takeaways

- The dataset contains **37,542 policies** with approximately **$187.8M in total claim amount**, an average claim amount of around **$5.0K**, and an overall claim frequency of **0.51**.

- **Private-use vehicles account for approximately 80% of total claim amount ($150.4M)**, compared with roughly **20% ($37.4M)** from commercial vehicles. This makes private-use policies the largest contributor to total claims exposure.

- Among vehicle manufacturers, **Ford generates the highest total claim amount at approximately $17M**, followed by **Chevrolet at $15M**, while the remaining leading manufacturers contribute noticeably smaller amounts.

- Claim amounts are distributed relatively evenly across **coverage zones**, with each zone contributing roughly one-fifth of the total. This suggests that overall claims exposure is not heavily concentrated in one geographic coverage category.

- Policyholders between **26 and 65 years old** generate the highest claim amounts, with each major age group in this range contributing approximately **$35M–$36M**.

- Claim amount decreases sharply as the **number of kids driving increases**. Policies with no kids driving account for approximately **$134M**, compared with $34M for one, $16M for two, and $4M for three kids driving. This pattern should be interpreted alongside the number of policies in each group before treating it as a difference in individual risk.

- **Single policyholders account for approximately $96.3M in claims**, the largest marital-status total, followed by married policyholders at approximately **$50.6M**. Further analysis using claim frequency or average claim amount could help determine whether this reflects higher policy volume or higher underlying risk.

These findings can support more detailed **customer segmentation and risk analysis**, while highlighting where normalized metrics such as claim frequency and average claim amount are important before making pricing or underwriting decisions.

---

## Tools & Skills

| Tool | Skills Demonstrated |
|---|---|
| **Power BI** | Dashboard design, interactive filtering, data visualization, KPI reporting |
| **DAX** | Measures, calculated fields, conditional logic, dynamic titles and measure selection |
| **Data Analysis** | Claims analysis, customer segmentation, risk pattern identification |
| **Business Analytics** | Translating insurance data into interpretable risk and customer insights |

---

## Repository Structure

```text
Insurance-Risk-Claims-Analysis/
│
├── README.md
├── insurance_risk_claims_dashboard.pbix
│
└── assets/
    └── insurance-dashboard.png
```

---

## Conclusion

This project demonstrates the use of **Power BI and DAX to explore insurance claims and customer risk patterns through an interactive dashboard**.

The analysis highlights differences across vehicle usage, demographics, vehicle characteristics, and customer segments while also showing the importance of considering both **claim totals and normalized risk metrics** when evaluating insurance performance.
