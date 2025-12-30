# Impact of Physical Activity on Blood Pressure: An NHANES Analysis

### Project Overview
**Authors:** Chris Coker, Isaac Graham, Rhiannon Stracener

**Tools Used:** R (Data Cleaning), JMP (Statistical Modeling)

This project analyzes the 2017-2018 NHANES dataset to determine if increased physical activity lowers blood pressure uniformly across different demographic groups. We utilized **R** for data engineering and **JMP** to build an ANCOVA model controlling for Age, Sex, BMI, and Alcohol Use.

### Key Findings
* **Unequal Slopes:** We found significant interactions indicating that physical activity does **not** affect everyone equally.
* **Systolic BP:** The benefits of activity vary significantly by **Age** and **Sex**.
* **Diastolic BP:** The benefits are dependent on **BMI** and **Alcohol Consumption**.

### Repository Structure
* **`results/Team12Project.pdf`**: **Start Here.** The full presentation slides containing our visualizations, ANOVA tables, and conclusions.
* **`data_and_analysis/Final Project JMP Analysis.jmp`**: The source JMP file containing the interactive ANCOVA models and data tables.
* **`data_and_analysis/nhanes_cleaned.csv`**: The processed CSV dataset.

---
*Note: To view the statistical models interactively, you will need JMP software installed. Otherwise, please refer to the PDF report in the results folder.*
