# Stock & Health Data Analysis 📊

## Overview
This project analyzes **stock market trends** and **health survey data** using R to uncover patterns, relationships, and actionable insights. It demonstrates multivariate statistical analysis, factor analysis, PCA, MANOVA, and data visualization.

---

## Stock Market Analysis

**Goal:** Identify hidden factors influencing stock prices.  
**Methods:** Factor Analysis (PC & MLE) and Principal Component Analysis (PCA) with Varimax rotation.  

**Key Insights:**  
- Three main factors:  
  1. Market leaders with diversified portfolios (e.g., Walmart, Apple).  
  2. Companies influenced by consumer spending trends (e.g., Amazon, Pepsi).  
  3. International giants in tech, consumer goods, and finance.  
- PCA revealed **Walmart, Apple, Toyota, and Amazon** as top influencers.  

**Impact:** Provides insights for portfolio analysis and investment strategies.  

**Tools:** `FactoMineR`, `psych`, `GPArotation`, `ggplot2`, `corrplot`.

---

## Health Metrics Analysis

### By Gender
**Goal:** Compare Age, Sleep Duration, and Heart Rate between **Male and Female** participants.  
**Method:** Hotelling’s T² test & multivariate normality checks.  

**Insights:** Significant differences were observed across all metrics.  
**Impact:** Useful for designing gender-specific wellness initiatives.  
**Tools:** `MVN`, `heplots`, `DescTools`.

### By Occupation
**Goal:** Compare Age, Sleep Duration, and Heart Rate across **Accountant, Doctor, Lawyer** groups.  
**Method:** MANOVA with Bonferroni-adjusted confidence intervals.  

**Insights:** Age, Sleep Duration, and Heart Rate vary significantly by occupation.  
**Impact:** Highlights occupation-specific health trends for targeted in
