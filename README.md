# Student Performance and Aptitude Analysis
## The Key English Course Company - Indonesia

A comprehensive statistical analysis validating the effectiveness of a course placement system using student aptitude scores and performance results.


<p align="center">
  <img src="assets/logo.png" alt="The Key" width="200">
</p>

# Project Overview

This project presents a rigorous statistical analysis of 150 students across three English course levels
(Advanced, Intermediate, Foundation) to validate the effectiveness of The Key's course placement system.
The study examines the relationship between aptitude test scores and actual performance to ensure
students are placed in appropriate learning environments.

## Key Findings

- ✅ **"Highly Significant Differences"**: Clear stratification across all course levels (p < .001)
- ✅ **"Strong Predictive Validity"**: Aptitude scores correlate strongly with performance (r = .887)
- ✅ **"Very Large Effect Sizes"**: All pairwise comparisons show Cohen’s d > 1.2
- ✅ **"System Validation"**: Placement procedures are working excellently


## Research Questions

1. Do students with different performance levels enroll in different course levels?
2. Are there significant differences in aptitude scores across course levels?
3. What is the correlation between aptitude scores and performance?
4. What are the implications for course placement and program quality?

## Repository Contents
.
├── ./README.md                        # This file
├── ./assets                           # Complete Jupyter notebook with all calculations/
│   └── ./assets                           # Complete Jupyter notebook with all calculations/logo.jpg                     # company logo         
├── ./analysis_notebook.ipynb          # analysis report        
├── ./report in progress.pdf           # analysis report
└── ./requirements.txt                 # Python dependencies

## 📦 Dataset & Methodology

**Dataset Contents:**
- `student_combined_data.csv` — combined dataset of students.
- Other supporting CSV files for raw inputs.

**Key Variables:**
- `course_level` – course assignment (Foundation, Intermediate, Advanced).  
- `aptitude_score` – initial aptitude test score.  
- `performance_score` – final performance outcome.

**Tools & Libraries:**
- Python (Pandas, SciPy, Statsmodels)  
- Jupyter Notebook  
- Matplotlib / Seaborn (visualization)

## 📊 Results Summary

### 🔹 1. Course Enrollment & Performance
Using group comparisons and statistical tests, we observe distinct performance patterns across course levels, suggesting that placement is associated with student outcomes.

- **Performance trend:** Advanced > Intermediate > Foundation  
- **Statistical evidence:** ANOVA/Kruskal results indicate significant differences.

### 🔹 2. Aptitude Differences
Aptitude scores also differ meaningfully between course levels, validating the test’s role in placement.

- **Group means differ significantly** across levels.

### 🔹 3. Aptitude vs Performance Correlation
Correlation analysis shows a strong positive relationship between initial aptitude scores and final performance outcomes.

- **Correlation coefficient (r)** indicates a strong relationship.