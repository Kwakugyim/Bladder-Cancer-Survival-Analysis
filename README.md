Bladder Cancer Survival Analysis

This project explores the recurrence of bladder cancer using survival analysis methods in R. We analyze patient data using **Kaplan-Meier curves**, the **log-rank test**, the **Cox proportional hazards model**, and **parametric models** (Weibull and Lognormal). The goal is to understand the impact of treatment and tumor characteristics on recurrence over time.

---

Methods Used

- **Descriptive Summary**
- **Kaplan-Meier Survival Estimation**
- **Log-Rank Test**
- **Cox Proportional Hazards Model**
- **Parametric Survival Modeling** (Weibull & Lognormal)
- Model comparison using **AIC values**

---

Folder Contents

| File/Folder         | Description                                                      |
|---------------------|------------------------------------------------------------------|
| `survival_analysis.R` | R script with all analysis steps                               |
| `report.pdf` or `.docx` | Final report with background, methods, results, and discussion |
| `presentation.pptx` | Layman-friendly summary of the findings                         |
| `plots/`            | Kaplan-Meier curves, parametric model plots, etc.               |
| `tables/` | Descriptive and analytical result tables                      |

---

Key Findings

- **Thiotepa** treatment significantly reduced the risk of cancer recurrence.
- Patients with **more tumors at diagnosis** had higher risk of recurrence.
- The **lognormal model** had slightly better fit than the Weibull model.
- Visual tools (KM curves, parametric plots) clearly showed differences between groups.

---

Software & Packages

- **R version 4.3.1**
- R packages used:
  - `survival`
  - `flexsurv`
  - `ggplot2`
  - `dplyr`

---

Author

This project was developed by Kwaku Gyimah as part of a graduate course in biostatistics.  
Feel free to reach out via GitHub or kgyimah@outlook.com.

---

References

- Kamat, A. M., et al. (2016). *Bladder cancer.* The Lancet.  
- Sylvester, R. J., et al. (2006). *EORTC risk tables.* European Urology.  
- Babjuk, M., et al. (2022). *EAU Guidelines.* European Urology.  
- R Core Team (2023). *R: A language and environment for statistical computing.*
