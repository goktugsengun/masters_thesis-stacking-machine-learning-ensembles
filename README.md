Maximizing Ensemble Model Performance by Introducing Diversity for Default Prediction

Welcome!

This repository contains the research, code, and supporting material from my master's thesis:

“Maximizing Ensemble Model Performance by Introducing Diversity for Default Prediction”

This project investigates how model diversity can significantly improve the predictive power of ensemble techniques, specifically within the context of credit risk and default prediction in financial markets.

Project Summary

Predicting loan or credit defaults is a critical task for financial institutions, directly impacting lending strategies, portfolio management, and risk assessment. Traditional models, although widely adopted, often fall short when confronted with the complexities and non-linear relationships inherent in financial datasets.

This thesis proposes and tests an ensemble approach — with a particular focus on stacking ensembles — to address this gap. The research explores how introducing diversity among base models enhances predictive performance and robustness, especially when facing:

Imbalanced datasets

High dimensionality

Missing or noisy values

The study provides both theoretical insights and practical implementations, comparing diverse stacking ensembles against widely used methods like Random Forest, XGBoost, and AdaBoost.

Key Contributions

Demonstrated how model diversity positively impacts ensemble learning performance.

Compared baseline models and stacking ensembles on real-world financial data.

Addressed core challenges like data imbalance, high dimensionality, and missing values.

Provided a framework for model evaluation using accuracy, AUC, F1-Score, and ensemble diversity metrics.

Offered insights for practitioners on the application of ensemble learning in financial risk management.

Libraries and Tools

This project is built using Python and the following libraries:

Pandas — Data manipulation and wrangling

NumPy — Scientific computing

Scikit-learn — Machine learning models & utilities

TensorFlow — Deep learning framework

SciKeras — Scikit-learn compatible Keras wrapper

imbalanced-learn — Handling class imbalance

XGBoost — Scalable gradient boosting

Statsmodels — Statistical modeling and testing

Matplotlib — Data visualization

Itertools — Efficient looping tools from Python's standard library

Results Overview

The research found that diverse stacking ensembles — built from models such as XGBoost, Random Forest, and neural networks — consistently outperformed single models and traditional boosting methods on default prediction tasks. This work highlights that diversity isn’t just a theoretical curiosity but a practical path to robust model performance in high-stakes financial contexts.

Keywords

Ensemble Models, Default Prediction, Financial Markets, Model Diversity, Binary Classification, Heterogeneous Classifier Ensembles, Advanced Predictive Modeling, Financial Risk Management.

Closing Note

This repository reflects both my technical skills and my enthusiasm for applying machine learning to real-world financial challenges. If you’re a recruiter, hiring manager, or fellow data enthusiast, feel free to reach out!




