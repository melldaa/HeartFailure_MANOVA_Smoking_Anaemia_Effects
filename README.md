📊 MANOVA Analysis on Heart Failure Clinical Records
This project applies Multivariate Analysis of Variance (MANOVA) to investigate the effects of smoking and anaemia on various clinical indicators in heart failure patients.

🧠 Objective
To analyze whether groups defined by smoking and anaemia differ significantly in terms of multiple dependent variables such as:
Serum sodium
Platelet count
Ejection fraction
Serum creatinine
Creatinine phosphokinase
Age
Time of follow-up

📁 Dataset
Source: heart_failure_clinical_records.xlsx

Content: Patient-level clinical variables (e.g., lab values, demographics, binary health indicators)

📌 Analyses Performed
✅ Data Preprocessing
Conversion of categorical variables (smoking, anaemia) into factors

Descriptive summaries and group sizes

📉 Visualization
Mean plots with 95% CI grouped by smoking and anaemia status

Interaction plots for visualizing variable interactions

📏 Assumption Checks
Multivariate normality (Shapiro–Wilk)

Box’s M Test for homogeneity of covariance

Levene’s Test for homogeneity of variances

🔬 MANOVA
Single-factor MANOVA: effect of smoking on clinical variables

Two-way MANOVA: interaction between smoking and anaemia

🧪 Post-Hoc Analysis
Univariate ANOVAs for each variable

Tukey HSD comparisons to assess group differences.

👩‍💻 Author
Melda Korkudan
Statistics graduate | R Programming | Data Analysis & Visualization

