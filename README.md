# Social-Media-vs-Productivity
Analyzed social media usage impact on individual productivity using Power BI &amp; Python

## Tools
- Power BI
- Python
- Excel

## Analysis Steps
- Data Cleaning
- Basic & Advanced Analysis
- Dashboard & Visualization

## Key Insights
- To be added after completing the project
## Data Cleaning / Preprocessing

The dataset contained missing values, inconsistent entries, and some outliers. The following steps were performed:

1. **Handling Missing Values**
   - Numeric columns (e.g., `sleep_hours`, `stress_level`) were imputed using the **median**.
   - Categorical columns (e.g., `job_type`, `gender`) were imputed using the **mode**.

2. **Data Type Validation**
   - Ensured all numeric columns are in numeric format.
   - Standardized categorical text columns (e.g., Male/Female, IT/EDUCATION).

3. **Outlier Review**
   - Reviewed extreme values (e.g., sleep_hours < 3 or > 12, social media time > 15 hours).
   - Values that were realistic but rare were kept; impossible values would be corrected or removed.

4. **Duplicates Removal**
   - Checked for duplicate rows and removed them.

5. **Feature Engineering**
   - Created additional columns such as `Productivity Gap = perceived_productivity_score - actual_productivity_score`.
