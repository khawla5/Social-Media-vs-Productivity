# Social Media vs Productivity

Analyzing the impact of social media usage on individual productivity using **Power BI** and **Python**.

This project explores how social media usage, sleep patterns, stress levels, and daily habits influence productivity and digital wellbeing.

---

# Tools

* Power BI
* Python
* Excel

---

# Analysis Steps

1. Data Cleaning
2. Exploratory Data Analysis (EDA)
3. Basic & Advanced Analysis
4. Feature Engineering
5. Segmentation
6. Dashboard & Visualization
7. Key Insights

---

# Data Cleaning / Preprocessing

The dataset contained missing values, inconsistent entries, and some outliers. The following steps were performed:

## Handling Missing Values

* Numeric columns (e.g., `sleep_hours`, `stress_level`) were imputed using the **median**.
* Categorical columns (e.g., `job_type`, `gender`) were imputed using the **mode**.

## Data Type Validation

* Ensured all numeric columns are in numeric format.
* Standardized categorical text columns (e.g., Male/Female, IT/EDUCATION).

## Outlier Review

* Reviewed extreme values (e.g., `sleep_hours < 3` or `> 12`, `social_media_usage > 15` hours).
* Realistic but rare values were kept.
* Impossible values would be corrected or removed.

## Duplicates Removal

* Checked for duplicate rows and removed them.

## Feature Engineering

Created new feature:

**Productivity Gap = perceived_productivity_score - actual_productivity_score**

This feature helps measure the difference between perceived and actual productivity.

---

# Exploratory Data Analysis (EDA)

In this phase, we aim to understand the story inside the data before building the dashboard.

## General Questions

* What is the average sleep hours?
* What is the average actual productivity?
* What is the average perceived productivity?
* Is stress level generally high?
* What is the average social media usage?

---

## Sleep Analysis

### Sleep Range

* Minimum sleep hours
* Maximum sleep hours
* Average sleep hours

### Sleep by Job Type

* How sleep varies across different job types
* Comparison between employees, students, and freelancers

### Sleep vs Stress

* Relationship between low sleep and stress
* Impact of sleep on stress level

### Sleep vs Productivity

* Impact of sleep on actual productivity
* Impact of sleep on perceived productivity
* Productivity gap based on sleep hours

---

## Social Media & Productivity

* Impact of social media on actual productivity
* Impact of social media on perceived productivity
* Relationship between social media and stress
* Impact of social media on sleep hours

---

# Basic Analysis

Summary statistics and distribution charts were created using Power BI.

### Summary Statistics

* Average Sleep Hours
* Average Stress Level
* Average Social Media Usage
* Average Productivity
* Average Work Hours

### Distribution Analysis

* Sleep distribution
* Stress distribution
* Social media usage distribution
* Productivity distribution

---

# Relationship Analysis

Scatter plots and comparisons were used to explore relationships between variables.

* Sleep vs Productivity
* Social Media vs Stress
* Stress vs Productivity
* Perceived vs Actual Productivity
* Work Hours vs Productivity

---

# Feature Engineering

Additional features were created to enhance analysis.

* Productivity Gap
* Sleep Category (Low / Normal / High)
* Stress Category (Low / Medium / High)

These features help segment users and improve dashboard analysis.

---

# Segmentation Analysis

Data was analyzed across different categories.

* Job Type
* Gender
* Sleep Category
* Stress Category
* Social Media Usage

### Examples

* Stress by Job Type
* Productivity by Job Type
* Sleep by Job Type
* Social Media Usage by Job Type
* Burnout vs Stress
* Job Satisfaction by Gender

---

# Basic Analysis Insights

* Most users sleep between 6 and 7 hours, which falls within the normal range.
* Stress levels appear moderate across the dataset.
* Social media usage varies across individuals.
* A noticeable gap exists between perceived and actual productivity.
* Some users show higher stress levels with lower sleep hours.

---

# Advanced Insights

* Lower sleep hours are associated with higher stress levels.
* Higher social media usage tends to reduce actual productivity.
* Employees experience higher stress compared to students.
* Users with high stress levels tend to have lower productivity.
* Productivity gap indicates that some users overestimate their performance.
* Digital wellbeing and breaks during work may improve productivity and reduce stress.

---

# Dashboard

The Power BI dashboard includes:

* KPI Cards (Sleep, Stress, Productivity, Social Media)
* Sleep vs Productivity Scatter Plot
* Stress by Job Type
* Social Media vs Stress
* Productivity Comparison
* Job Satisfaction Analysis
* Slicers (Job Type, Gender, Sleep Category)

Dashboard screenshots are available in the **images** folder.

---

# Project Structure

```
Social-Media-vs-Productivity
│
├── data
├── docs
├── images
├── powerbi
│     social_media_analysis.pbix
│
├── README.md
└── social_media_vs_productivity.csv
```

---

# Key Insights

* Sleep plays a significant role in productivity.
* Social media usage impacts stress and performance.
* Stress negatively affects productivity.
* Job type influences sleep and stress levels.
* Digital habits affect daily performance and wellbeing.

---

# Conclusion

This project demonstrates how data analysis and visualization can uncover meaningful insights about digital habits, stress, sleep, and productivity.

Using **Power BI and Python**, the analysis provides a clear data story that helps understand how social media usage affects individual productivity and wellbeing.

---

# Author

Khawla

Data Analysis Project using Power BI and Python
