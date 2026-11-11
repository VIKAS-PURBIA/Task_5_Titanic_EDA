# Task 5 – EDA Interview Questions and Answers

1. **What is EDA and why is it important?**  
   Exploratory Data Analysis (EDA) examines a dataset using summary statistics and visualizations before formal modeling. It helps understand structure, distributions, missing values, outliers, relationships, data-quality issues, and possible hypotheses. EDA guides cleaning and feature engineering.

2. **Which plots do you use to check correlation?**  
   A correlation heatmap displays many pairwise correlations. Scatterplots inspect two numeric variables and can reveal nonlinear patterns or outliers. Pairplots compare multiple numeric variables. Pearson measures linear association; Spearman is useful for monotonic relationships or ranked data.

3. **How do you handle skewed data?**  
   Inspect histograms, boxplots, and skewness. Report median and IQR in addition to mean and standard deviation. Depending on the variable and objective, consider log1p, square-root, or power transformations, robust scaling, or non-parametric methods. Do not transform automatically; preserve interpretability and check assumptions.

4. **How do you detect multicollinearity?**  
   Use a correlation matrix as an initial screen, then calculate Variance Inflation Factor (VIF) for predictors in a regression setting. High VIF suggests a predictor is explained by other predictors. Consider removing redundant features, combining features, or regularization. Thresholds are guidelines, not absolute rules.

5. **What are univariate, bivariate, and multivariate analyses?**  
   Univariate studies one variable (e.g., Age histogram). Bivariate studies two variables (e.g., survival by sex). Multivariate examines three or more variables together (e.g., pairplot or survival by sex and class).

6. **Difference between heatmap and pairplot?**  
   A heatmap uses color to represent values in a matrix, commonly correlation coefficients. It is compact for spotting positive or negative correlations. A pairplot creates pairwise scatterplots and univariate distributions; it reveals clusters, spread, outliers, and nonlinear patterns but can become crowded.

7. **How do you summarize your insights?**  
   State dataset size and quality, highlight important patterns with supporting statistics, describe what each visualization shows, mention missing values and outliers, and explain implications and limitations. Separate observed association from causation and provide clear next steps.
