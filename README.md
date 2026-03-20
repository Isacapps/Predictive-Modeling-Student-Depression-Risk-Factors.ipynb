Predictive Analysis of Mental Health Determinants in Student Populations
Abstract
This research project implements a supervised machine learning framework to identify and classify depression risk factors among students. By analyzing a dataset of over 27,000 observations, the study explores the intersection of academic pressure, socio-economic status, and lifestyle habits to provide a data-driven perspective on student well-being.

Research Objectives
- Risk Classification: Develop high-precision models to categorize individuals based on depressive symptom indicators.
- Feature Criticality: Quantify the impact of variables such as 'Financial Stress', 'Academic Pressure', and 'Study Satisfaction'.
- Lifestyle Correlation: Evaluate the statistical significance of sleep patterns and dietary habits in predicting mental health outcomes.

Dataset Taxonomy
The study utilizes a multi-dimensional dataset comprising 18 features across four primary domains:
- Demographics: Age, Gender, City, and Profession.
- Academic Metrics: Degree type, CGPA, Academic Pressure, and Study Satisfaction.
- Lifestyle Factors: Sleep Duration, Dietary Habits, and Daily Study/Work Hours.
- Clinical Indicators: Family History of Mental Illness, Suicidal Thoughts, and Financial Stress levels.

Methodology: Data Preprocessing
To ensure the integrity of the statistical inference, a comprehensive preprocessing pipeline was executed:
- Missing Value Management: Systematic imputation or removal of incomplete records to maintain dataset balance.
- Categorical Encoding: Implementation of One-Hot Encoding and Ordinal Mapping to translate qualitative descriptors (e.g., 'Sleep Duration') into computationally viable formats.
- Outlier Mitigation: Statistical filtering of non-physiological values in continuous features (e.g., Age and Study Hours) to reduce model variance.
- Feature Scaling: Standardizing numerical inputs to a uniform scale, preventing magnitude bias during algorithmic training.
- Target Encoding: Harmonizing the 'Depression' label for binary classification tasks.

Technical Framework
- Language: Python 
- Key Libraries: Pandas (Data Manipulation), Scikit-Learn (Machine Learning), Seaborn & Matplotlib (Exploratory Data Analysis).
- Evaluation Metrics: Focus on Recall and F1-Score to minimize false negatives, ensuring that at-risk individuals are not overlooked by the model.

Project Deliverables
- Analysis Notebook: Python implementation of the end-to-end ML pipeline.
- Research Presentation: Detailed slide deck summarizing findings and clinical insights.
- Visual Assets: High-resolution infographics and correlation matrices.

Authors
- Isabella Cappiello
- Nathan Dubourg
- Romain Sartori
