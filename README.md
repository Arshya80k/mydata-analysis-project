# Breast Cancer Gene Data Analysis

This is my first mini solo project to exercises my newly learned technical skills in data analysis.

## Key Biological Questions
1. How do expression levels of BRCA1, TP53, ERBB2, and EGFR shift as a tumour progresses from Stage 0 to Stage IV?

2. Does the age at diagnosis have a different impact on survival in localized versus metastatic cohorts?

3. Can we identify a molecular "switch" in gene expression that indicates a transition to advanced disease?

## Stages
* **Stage 1: Python Based Engineering** Used Pandas for initial data cleansing such as Handled missing values, narrowing data to only keep the relavent columns, correcting int to str formats and created an initial visualisation to check the data.
* **Stage 2: Excel Audit & Validation** Before visualising, I performed a second validation using Excel Pivot Tables to verify that mean expression levels across cohorts matched my Python outputs.
* **Stage 3: Interactive Analytics in Tableau** Built a dashboard that classified patients into Early (0-II) and Advanced (III-IV) cohorts. I implemented dashboard actions to allow for real time filtering, linking molecular signatures directly to survival outcomes.

## Key Findings
...

## Files
* `breast_cancer_clinical_final_pythonCode.ipynb`: The Python code used for cleaning.
* `breast_cancer_clinical_final.csv`: The processed dataset ready for Tableau.
* [The Interactive Clinical Dashboard on Tableau Public](https://public.tableau.com/views/breast_cancer_analysis/Dashboard1?:language=en-GB&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
