# Week 7 – Feature Selection and PCA

## Project
Moneyball: IPL Player Valuation

## Objective
- Identify numerical features.
- Analyse correlations between numerical features.
- Perform feature selection.
- Apply Principal Component Analysis (PCA).
- Reduce dimensionality while retaining important information.

## Dataset
Week6_Feature_Engineered_Dataset.csv

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Activities Completed

1. Loaded and inspected the IPL auction dataset.
2. Identified numerical features.
3. Analysed missing values.
4. Imputed missing numerical values using the median for PCA analysis.
5. Generated a numerical feature correlation heatmap.
6. Examined feature variance.
7. Removed constant features.
8. Standardized numerical features using StandardScaler.
9. Applied Principal Component Analysis.
10. Visualized explained variance and cumulative explained variance.
11. Generated a PCA scatter plot.
12. Examined PCA component loadings.
13. Exported the selected features and PCA results as CSV files.

## Results

- Original dataset shape: 2700 rows × 12 columns
- Numerical feature count: 4
- Features after constant-feature removal: 4
- Principal components required for 95% variance: 3
- Cumulative variance explained: 95.71%
- PCA reduced dataset shape: 2700 rows × 3 components

## Key Finding

PCA reduced the numerical feature dimensions from 4 to 3 principal components while retaining 95.71% of the variance.

This demonstrates dimensionality reduction while preserving most of the variation in the selected numerical data.

## Output Files

- Week7_Explained_Variance.csv
- Week7_PCA_Loadings.csv
- Week7_PCA_Reduced_Dataset.csv
- Week7_Selected_Numerical_Features.csv
- Week_7_Feature_Selection_PCA.ipynb

## Limitations

- Missing numerical values were imputed for PCA analysis using median values.
- PCA results depend on the selected features and preprocessing methods.
- Dimensionality reduction alone does not establish which IPL player offers the best value.
- Further validation is required before using these components for player valuation.

## Conclusion

Week 7 successfully demonstrated numerical feature selection, standardization, and PCA on the IPL auction dataset. Three principal components retained 95.71% of the variance in the selected numerical features.

## Next Week

Develop an interactive dashboard to communicate the project's findings through visualizations.
