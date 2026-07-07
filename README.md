## Data Cleaning Process (Excel Power Query)
Raw dataset: 5,050 rows × 17 columns → Cleaned: 5,000 rows × 17 columns

- Imputed missing values (Gender, Job_Level, Age_Group, Employment_Type, Educational_Level → mode; Salary, Performance_Score, Absenteeism → median)
0 rows dropped
- Removed duplicate Employee IDs
50 removed
- Standardized data types across all columns
0 format errors
- Trimmed & title-cased text fields
Uniform formatting
- Formatted salary as ₦ currency (2dp)
- Sorted Department/Employment_Type for aggregation
## Quality check 
0 duplicates, 0 nulls, 0% format errors on final dataset.

## Key Insight
Turnover is not evenly distributed across salary tiers — it's concentrated in one department. Sales has only 53.6% active staff (vs 65–73% elsewhere), a 32.1% resignation rate (nearly double every other department), the lowest average performance score (3.09 vs 3.5–3.6 company-wide), and the lowest average salary (₦306K vs ₦318K–₦425K elsewhere). Contract employees also resign at a notably higher rate (31.8%) than full-time staff (20.5%).

## Recommendation
Prioritize a Sales-specific retention review (compensation benchmarking + manager support) rather than a blanket salary adjustment, since pay alone doesn't explain turnover in other departments.
