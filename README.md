# Predictive_Modeling_of_Newborn_Birth_Weight


This repository contains a two-part statistical analysis project focused on exploring relationships within a dataset related to weight, height, sex, and hospital data. The analysis is conducted in R, with emphasis on both descriptive and inferential techniques, including linear modeling and diagnostic evaluation.

---

## Project Structure

### Part 1: Preliminary Exploration

1. **Import Dataset**
   - Load and inspect the dataset.

2. **Dataset Description**
   - Overview of dataset structure and variable types.
   - Categorization of variables (numerical, categorical, etc.).

3. **Goal**
   - Understand basic patterns and assess assumptions of data independence.

4. **Descriptive Analysis**
   - Summary statistics and visualizations.

5. **Compare to Literature**
   - Check if average weight and height align with reference literature.

6. **Sex-Based Differences**
   - Analyze differences in key variables (e.g., weight, height) between male and female newborns.

7. **Hospital Comparison**
   - Compare distributions and averages across different hospitals.

---

### Part 2: Modeling & Prediction

1. **Relationships Between Variables**
   - Explore correlations and visual relationships.

2. **Multiple Linear Regression**
   - Build models predicting weight based on other variables.

3. **Best Model Selection**
   - Use AIC, adjusted R², or other criteria to determine the best-fitting model.

4. **Non-Linear Effects**
   - Investigate and model potential non-linear relationships (e.g., using splines or transformations).

5. **Model Diagnostics**
   - Evaluate model assumptions, residuals, and fit.

   5.1 **Outlier Detection**
   - Identify and assess influential points and leverage.

6. **Prediction Check**
   - Evaluate prediction accuracy using cross-validation or test sets.

7. **Model Predictions**
   - Generate predictions and compare with actual outcomes.

8. **Graphical Representation**
   - Visualize models and predictions using ggplot2 and other tools.

---



## R version

- **Language**: R (≥ 4.3)
- **Key Libraries**:
  - `tidyverse`
  - `summarytools`
  - `ggplot2`
  - `car`
  - `caret`
  - `splines`
  - `broom`

---

## Notes
I encountered some issues after updating R (which turned out to be a poor decision). I tried rerunning everything using R version 4.5, but a few packages no longer work correctly. As a workaround, (and because i didn't want to the downgrade) I converted a previously saved `.html` report into a PDF instead.
---



