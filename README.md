# Salary Comparison Analysis

In this analysis, I explore the differences in average salaries based on gender and education levels using statistical methods.

## Gender-based Salary Comparison

To assess whether the mean salaries between males and females are statistically different, descriptive statistics were produced for the two groups. The mean salaries were found to be $66,384.40 for males and $48,630.61 for females, with standard deviations of $119,863.61 and $96,112.55 respectively.

Given the non-homogeneity of variances between the two groups, Welch’s T-test was conducted. Despite the presence of outliers, which accounted for 9.36% and 5.72% of male and female instances respectively, they were retained in the dataset prior to the T-test. The resulting p-value of 2.76e-09 and T-stat of 5.97 indicate a statistically significant difference in mean salaries between genders.

Subsequently, the data was bootstrapped, with 2/3 of the total instances from each group sampled over 10,000 replications. Another T-test on the bootstrapped mean salaries yielded a p-value of 486.37 and a T-stat of 0, further confirming the significant difference in mean salaries between men and women.

## Education-based Salary Comparison

Next, the analysis extended to estimating the difference in average salaries based on education levels. The mean salaries for individuals with bachelor’s, master’s, and doctoral degrees were calculated as $53,855.11, $65,620.12, and $84,376.94 respectively.

Due to non-homogeneous variances between education groups, Welch’s ANOVA test was performed, resulting in an F-value of 23.97 and a p-value of 4.66e-11. Similar to the gender-based analysis, outliers were identified using the same methods and retained in the dataset.

Bootstrapping was applied to the data, and the resulting distributions were analyzed. ANOVA conducted on the mean salaries yielded a p-value of 202986 and a T-stat of 0, indicating a statistically significant difference in mean salaries across education levels.

This analysis provides valuable insights into the disparities in average salaries based on gender and education levels, highlighting the importance of statistical techniques in uncovering underlying patterns in salary data.
