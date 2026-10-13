# Generic Undergraduate Syllabus: Applied Data Science Methods

**Level:** Upper-year undergraduate  
**Indicative duration:** 12 teaching weeks  
**Prerequisite assumptions:** Introductory data science methods, probability/statistics, and programming

## Course description
Students compare statistical and machine-learning methods for prediction, classification, and unsupervised learning. They learn to validate models, diagnose limitations, and communicate results scientifically. Model choice is tied to the question, data structure, assumptions, and cost of errors.

## Learning outcomes
Students should be able to:
1. Build reproducible data-preparation and modelling pipelines.
2. Fit and interpret multiple linear and logistic regression models.
3. Explain and apply Ridge and LASSO regularization.
4. Compare classification methods using appropriate metrics and decision thresholds.
5. Fit and interpret decision trees, random forests, bagging, and boosting.
6. Explain generalized additive models and their use cases.
7. Apply PCA/SVD for dimension reduction and interpret component limitations.
8. Use cross-validation and bootstrap appropriately.
9. Explain multiple hypothesis testing and the risks of uncorrected comparisons.
10. Communicate model assumptions, uncertainty, performance, and limitations.

## Indicative weekly schedule
| Week | Topics | Practical evidence |
|---|---|---|
| 1 | Workflow review, data leakage, preprocessing and pipelines | Pipeline exercise |
| 2 | Multiple linear regression, assumptions and diagnostics | Regression notebook |
| 3 | Model selection, interactions, transformations and feature engineering | Model diagnostics |
| 4 | Logistic regression, classification threshold and probability | Classification lab |
| 5 | Confusion matrix, sensitivity, specificity, precision, recall, ROC/AUC | Metrics comparison |
| 6 | Decision trees, interpretability and overfitting | Tree lab |
| 7 | Bagging, random forests and feature importance limitations | Ensemble comparison |
| 8 | Boosting for trees and linear models; model comparison | Boosting exercise |
| 9 | Ridge, LASSO, regularization and bias–variance | Regularization lab |
| 10 | Generalized additive models and nonlinear relationships | GAM exploration |
| 11 | PCA/SVD, dimension reduction, multiple testing and resampling | PCA/resampling lab |
| 12 | Integrated modelling project, scientific communication and review | Final project |

## Assessment blueprint (adaptable)
- Technical labs and notebooks: 20%
- Model evaluation assignment: 20%
- Midterm concept and interpretation assessment: 15%
- Team or individual applied modelling project: 30%
- Scientific communication/report: 15%

## Required practices
- Separate training and test data before data-dependent preprocessing.
- Use cross-validation for model selection, not the final test set.
- Report metrics that match the application and consequences of errors.
- Compare against a simple baseline.
- Document random seeds, packages, data sources, and limitations.
- Discuss ethical risks, potential bias, privacy, and interpretability.
