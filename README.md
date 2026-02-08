# Drug Safety Clinical Data Analysis Project
## Project Background

I obtained a clinical-style drug safety dataset designed to evaluate the safety profile of a medication compared to a placebo control. The dataset contains patient-level information including treatment group, occurrence of adverse effects, number of side effects experienced, laboratory blood parameters, and demographic variables such as age and sex.

Given my interest in clinical data analysis and medication safety, I used this dataset to perform a structured statistical evaluation of whether the drug shows any safety concerns when compared to placebo.

This project simulates the type of analysis performed in clinical trials, pharmacovigilance, and post-marketing drug surveillance.

## Objectives of the Analysis

The main goal of this project was to assess drug safety using statistical methods. Specifically, I aimed to:

Compare the proportion of patients experiencing adverse effects
Determine whether the drug increases the overall risk of side effects compared to placebo.

Evaluate the number of side effects per patient
Assess whether patients on the drug experience a greater burden or frequency of side effects.

Check baseline comparability between treatment groups
Analyze age distribution to ensure that any safety differences are not due to demographic imbalance.


## Statistical Approach

To answer these questions, I applied statistical hypothesis testing:

Two-Proportion Z-Test to compare adverse effect rates

Chi-Square Test of Independence to examine differences in the number of side effects

Normality testing (Shapiro–Wilk) to determine appropriate statistical tests for continuous variables

Mann–Whitney U Test to compare age distributions between groups

These methods allowed for an evidence-based evaluation of whether observed differences were statistically significant or likely due to chance.

## Key Findings

After conducting the analysis, the results showed:

There was no significant difference in the proportion of patients experiencing adverse effects between the drug and placebo groups.

The number of side effects per patient was not significantly associated with treatment type.

The age distribution between the drug and placebo groups was statistically similar, indicating a fair comparison between groups.


## Conclusion

Based on the statistical evidence from this dataset, the drug demonstrates a safety profile comparable to placebo. There is no indication of increased overall side-effect risk or higher side-effect burden among patients receiving the drug.

This project demonstrates how statistical analysis can be used in healthcare and pharmaceutical research to support data-driven medication safety decisions.

## Tools & Libraries Used

Python

pandas

seaborn & matplotlib

statsmodels

pingouin
