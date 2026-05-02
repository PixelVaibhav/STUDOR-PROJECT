# PathAI — Student Engagement & Risk Prediction System

## Overview

This project builds a data-driven system to analyze student behavior and improve academic outcomes. It focuses on identifying disengaged students early and recommending suitable learning pathways.

The solution is based on the Open University Learning Analytics Dataset (OULAD), which contains student interaction, assessment, and outcome data.

---

## Key Components

### 1. Engagement Scoring System

A dynamic engagement score (0–100) is computed using:

* Student activity (VLE clicks)
* Assessment performance

This score tracks how student engagement evolves over time.

---

### 2. Disengagement Prediction Model

A machine learning model (Logistic Regression) predicts whether a student is at risk of failing or withdrawing before Week 6.

* Features: activity + performance
* Class balancing used to improve recall
* Output: risk probability for each student

---

### 3. Course Recommendation System

A content-based recommendation approach suggests the top 3 courses based on historical student performance.

---

## Key Insights

* Low engagement is a strong early indicator of dropout risk
* Early prediction enables proactive intervention
* Data-driven recommendations can guide better academic decisions

---

## How to Run

1. Install dependencies:
   pip install -r requirements.txt

2. Open the notebook:
   notebooks/01_data_understanding.ipynb

3. Run all cells

---

## Future Improvements

* Add more behavioral features (recency, trends, consistency)
* Implement collaborative filtering for recommendations
* Improve model with advanced algorithms
* Add real-time monitoring dashboard

---

## Author

[Your Name]
