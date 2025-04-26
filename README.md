# 📅 Course Schedule

| Week | Lecture | Lab | Task |
|:----:|:--------|:---:|:----:|
| 1 | Course Outline & Introduction | Machine Learning Revision - Lab 1 | |
| 2 | Interpretable Models - Part 1 | Machine Learning Revision - Lab 2 | |
| 3 | Interpretable Models - Part 2 | Exploratory Data Analysis and Feature Engineering - Lab 1 | Project Document Release + Team Formation |
| 4 | Global Model-Agnostic Methods Part 1 | Exploratory Data Analysis and Feature Engineering - Lab 2 | Project Idea Submission |
| 5 | Global Model-Agnostic Methods Part 2 | GAM, Decision Trees and Random Forests Lab | |
| 6 | Local Model-Agnostic Methods Part 1 | Features Importance Analysis Lab | |
| 7 | Local Model-Agnostic Methods Part 2 | Lab Exam 1 | Project Phase 1 Delivery |
| 8 | Midterm | | |
| 9 |  | Eid Vacation | |
| 10 | Neural Network Interpretation - 1 | Local Model-Agnostic Methods Lab | |
| 11 | Neural Network Interpretation - 2 | Neural Networks Explanation Lab | |
| 12 | Time Series Analysis Algorithms and EDA Techniques - Part 1 | Case Study Lab | |
| 13 | Time Series Analysis Algorithms and EDA Techniques - Part 2 | Lab Exam 2 | |
| 14 | Case Study - Computer Vision | Project Phase 2 | |

---

# 📚 Labs Content

## Table of Contents
- [Lab 7 - Local Agnostic Methods](#lab-7---local-agnostic-methods)
  - [Partial Dependence Plot (PDP)](#partial-dependence-plot-pdp)
  - [Individual Conditional Expectation (ICE) Plot](#individual-conditional-expectation-ice-plot)
  - [Accumulated Local Effects (ALE) Plot](#accumulated-local-effects-ale-plot)
  - [Permutation Feature Importance](#permutation-feature-importance)
  - [LOFO (Leave One Feature Out) Importance](#lofo-leave-one-feature-out-importance)
  - [Global Surrogate Model](#global-surrogate-model)
  - [Feature Interaction: H-Statistic](#feature-interaction-h-statistic)
- [Lab 8 - Global Agnostic Methods](#lab-8---global-agnostic-methods)
  - [LIME](#lime-local-interpretable-model-agnostic-explanations)
  - [SHAP](#shap-shapley-additive-explanations)

---

# Lab 7 - Local Agnostic Methods

## Partial Dependence Plot (PDP)
- **Description**: Shows how a feature affects the predicted outcome on average.
- **Documentation**: [Partial Dependence Plot - Scikit Learn](https://scikit-learn.org/stable/auto_examples/miscellaneous/plot_partial_dependence_visualization_api.html)

## Individual Conditional Expectation (ICE) Plot
- **Description**: Like PDP, but shows the effect for each individual observation separately.

## Accumulated Local Effects (ALE) Plot
- **Description**: Better than PDP when features are correlated. Shows the effect of a feature by considering small changes.
- **Documentation**: [ALE Plot - Alibi Documentation](https://docs.seldon.io/projects/alibi/en/latest/examples/ale_classification.html)

## Permutation Feature Importance
- **Description**: Measures how much the model's performance drops when a feature's values are randomly shuffled.

## LOFO (Leave One Feature Out) Importance
- **Description**: Measures feature importance by removing one feature at a time and checking how the model's performance changes.

## Global Surrogate Model
- **Description**: Train a simple model (like decision tree) to approximate and explain the behavior of a complex model.

## Feature Interaction: H-Statistic
- **Description**: Measures how strongly two or more features interact and influence the prediction.

---

# Lab 8 - Global Agnostic Methods

## LIME (Local Interpretable Model-Agnostic Explanations)
- **Description**: Explains a prediction by training a simple interpretable model around a local area of that prediction.
- **Documentation**: [LIME Documentation](https://lime-ml.readthedocs.io/en/latest/index.html)

## SHAP (SHapley Additive exPlanations)
- **Description**: Explains predictions by fairly distributing the contribution among features based on Shapley values from game theory.
- **Documentation**: [SHAP Documentation](https://shap.readthedocs.io/en/latest/index.html)
