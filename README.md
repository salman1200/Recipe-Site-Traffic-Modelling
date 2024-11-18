# Predicting Popular Recipes

This project focuses on identifying and promoting recipes that are likely to attract high traffic to our website. By leveraging data-driven insights and a logistic regression model, the goal is to enhance user engagement and increase website subscriptions.

---

## Problem Statement

- **Goal**: Automatically identify recipes that are more likely to become popular.
- **Challenge**: Current recipe selection process is manual and disconnected from user interests.
- **Impact**: Improving user engagement and driving website subscriptions by showcasing the right recipes.

---

## Data Overview

The dataset includes various recipe features:
- **Key Features**: Recipe number, category, nutritional content (calories, carbs, sugars, proteins), servings, and historical traffic data.
- **Traffic Labels**: High vs. low traffic recipes.

---

## Insights and Findings

- Popular categories: **Vegetable, Potato, and Pork** recipes generate the most traffic.
- Less popular categories: **Chicken, Breakfast, and Beverage** recipes.
- Nutritional features like calories, protein, and sugars do not significantly influence traffic.

---

## Methodology

- **Model Used**: Logistic Regression.
- **Performance**: Achieved 76% accuracy in classifying recipes as high or low traffic.

---

## Metric: High-Traffic Recipe Rate

- **Definition**: Percentage of recipes classified as high-traffic.
- **Monitoring**:
  - **Frequency**: Monthly.
  - **Threshold**: Target rate of 60.61% (baseline from initial analysis).
- **Importance**: Helps refine content strategy and boosts user engagement.

---

## Recommendations

1. **Prioritize Posting**:
   - Focus on high-traffic categories like **Vegetable, Potato, and Pork** recipes.
2. **Continuous Evaluation**:
   - Monitor the High-Traffic Recipe Rate monthly and adjust strategy as needed.

---

## Future Steps

Enhance the predictive model and integrate automated systems to improve recipe selection accuracy, enabling a seamless content strategy aligned with user preferences.

---

Thank you for exploring this project!
