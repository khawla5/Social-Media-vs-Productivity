# Social Media vs Productivity

Analyzing the impact of social media usage on individual productivity using **Power BI** and **Python**.

---

## Tools

* Power BI
* Python
* Excel

---

## Analysis Steps

1. Data Cleaning
2. Exploratory Data Analysis (EDA)
3. Basic & Advanced Analysis
4. Dashboard & Visualization
5. Key Insights

---

## Data Cleaning / Preprocessing

The dataset contained missing values, inconsistent entries, and some outliers.
The following steps were performed:

### Handling Missing Values

* Numeric columns (e.g., `sleep_hours`, `stress_level`) were imputed using the **median**.
* Categorical columns (e.g., `job_type`, `gender`) were imputed using the **mode**.

### Data Type Validation

* Ensured all numeric columns are in numeric format.
* Standardized categorical text columns (e.g., Male/Female, IT/EDUCATION).

### Outlier Review

* Reviewed extreme values (e.g., `sleep_hours < 3` or `> 12`, `social_media_usage > 15` hours).
* Realistic but rare values were kept.
* Impossible values would be corrected or removed.

### Duplicates Removal

* Checked for duplicate rows and removed them.

### Feature Engineering

* Created new feature:

`Productivity Gap = perceived_productivity_score - actual_productivity_score`

This feature helps measure the difference between perceived and actual productivity.

---

## Exploratory Data Analysis (EDA)

In this phase, we aim to understand the story inside the data before building the dashboard.

### General Questions

* What is the average sleep hours?
* What is the average actual productivity?
* What is the average perceived productivity?
* Is stress level generally high?
* What is the average social media usage?

---

### Sleep Analysis

#### 1. Sleep Range

* What is the minimum sleep hours?
* What is the maximum sleep hours?
* What is the average sleep hours?

#### 2. Sleep by Job Type

* How does sleep vary across different job types?
* Do employees sleep less than students?
* Does freelance work affect sleep patterns?

#### 3. Sleep vs Stress

* Is low sleep associated with higher stress?
* Do people who sleep more experience less stress?

#### 4. Sleep vs Productivity

* Does sleep affect actual productivity?
* Does sleep affect perceived productivity?
* Do people who sleep more feel more productive?
* Is there a gap between perceived and actual productivity when sleep decreases?

---

### Social Media & Productivity

* Does social media usage reduce actual productivity?
* Does social media increase perceived productivity?
* Is high social media usage linked to higher stress?
* Does social media affect sleep hours?

---

## Key Insights

To be added after completing the project.

---

## Dashboard

To be added after building Power BI dashboard.
