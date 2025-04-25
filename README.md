# Gage R&R Study - ANOVA Method (Minitab)

This project showcases a Gage Repeatability and Reproducibility (Gage R&R) study conducted using the **ANOVA method** via Minitab software. It includes the raw data (Excel format) and visual/statistical analysis outputs from Minitab.

---

## 📁 Files and Structure

### `/data/02_05_LCM.xls`
- Contains measurement data collected across multiple parts and operators.
- Data is used to assess the measurement system's consistency and reliability.

### `/screenshots/`
- **anova_table.png**  
  Contains the two-way ANOVA table with interaction, variance components table, and % contribution of each source of variation.

- **gage_rr_charts.png**  
  Composite report showing:
  - Components of variation (% contribution, study variation, % tolerance)
  - R Chart by operators
  - X̄ Chart by operators
  - Boxplot of measurement by parts
  - Boxplot of measurement by operators
  - Interaction plot (Parts * Operators)

- **gage_eval_probs.png**  
  Includes:
  - Gage evaluation table (StdDev, Study Var, %SV, %Tolerance)
  - Number of distinct categories
  - Joint and Conditional probabilities of misclassification

---

## 🔬 Key Insights

### ANOVA Table
- **Parts**, **Operators**, and **Part × Operator interaction** are all statistically significant (p-value < 0.05).
- Indicates differences in measurements are influenced by part variability and operator performance.

### Variance Components
- **Part-to-Part** variation dominates (97.02% of total variation).
- **Total Gage R&R** accounts for only **2.98%**, indicating the measurement system is acceptable.

### Gage Evaluation
- Study variation is **16.72%**, and %Tolerance (SV/Toler) is **167.21%**.
- The measurement system has decent resolution: **8 distinct categories**.

### Misclassification Probabilities
- Small chance (1.3%) that a good part is wrongly rejected.
- Slightly lower chance (0.9%) of a bad part being wrongly accepted.

---

## 📌 Conclusion

This Gage R&R study confirms the measurement system is **acceptable** with low variation due to repeatability and reproducibility. Most variation is from the parts themselves, which is ideal.

---

## 💻 Software Used

- **Minitab Statistical Software**
- **Excel** for data organization

---

## 👤 Author

Pavankumar Harikrishna  
[Project for statistical quality analysis or similar coursework]

