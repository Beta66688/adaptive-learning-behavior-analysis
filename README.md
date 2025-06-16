# Adaptive Learning Behaviour and Performance Analysis

> Group project for AIDM7400 - Data Analysis and Visualization Studio  
> 📅 May 2025 | 👩‍🎓 HKBU | 🧠 Focused on learning styles, engagement, and academic outcomes

---

## 📌 Overview

This project explores the relationship between students’ adaptive learning behaviors and academic outcomes using interaction data from an online learning platform (10,000+ records). We investigated how learning styles, engagement levels, and time investment affect final scores and dropout likelihood.

---

## 🎯 Research Objectives

1. Does video-watching time correlate with final scores?
2. Do engagement levels impact academic performance or satisfaction?
3. Are there performance differences between learning styles?
4. How do behavioral patterns predict dropout risk?
5. Does the effect of video time vary across learning types?

---

## 🧪 Methods Used

- **Data Cleaning & EDA**: Pandas, Seaborn, Matplotlib
- **Statistical Testing**: T-tests, ANOVA, Tukey HSD
- **Regression Modeling**: Multiple Linear Regression (scikit-learn)
- **Behavioral Typing**: Median split + logistic regression
- **Visualization**: Heatmaps, density plots, bar charts, word clouds
- **Tools**: Python, Jupyter Notebook, Tableau

---

## 🔍 Key Findings

- 📉 **Reading/Writing learners** performed significantly worse than Auditory learners (p = 0.027)
- 🎥 **Video time** did not predict final scores overall, but had a **negative effect for Reading/Writing learners**
- 🧠 **High engagement** led to **higher course satisfaction**, but not necessarily higher scores
- ❗ **Disengaged students** had unexpectedly lower dropout rates than “independent explorers”
- 👶 **Auditory learners** were generally younger than Visual learners

---

## 📊 Sample Visualizations

| Topic | Sample |
|-------|--------|
| Correlation Heatmap | ![Correlation Heatmap](images/correlation_heatmap.png) |
| Average Video Time by Age | ![Video Time](images/video_time_by_age.png) |
| Learning Style vs Final Score | ![Final Score](images/final_score_by_style.png) |
