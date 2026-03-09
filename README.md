# Jamboree-Education---Linear-Regression
Jamboree in understanding what factors are important in graduate admissions and how these factors are interrelated among themselves. It will also help predict one's chances of admission given the rest of the variables.

Executive Summary
Jamboree Education aims to assist students in estimating their probability of admission into Ivy League colleges. This project utilizes Multiple Linear Regression and Regularization techniques (Ridge/Lasso) to identify the core drivers of graduate admissions.

Key Finding: Undergraduate GPA (CGPA) and GRE Scores are the most significant predictors, while Research Experience provides a marginal but distinct "competitive edge."


The Data
The dataset contains 500 records of graduate applicants with the following features:

GRE Score: (0 to 340)

TOEFL Score: (0 to 120)

University Rating: (1 to 5)

SOP & LOR: (1 to 5)

CGPA: (0 to 10)

Research: (0 or 1)

Chance of Admit: (0.34 to 0.97) — Target Variable

The "CGPA" Threshold: CGPA has a linear correlation with admission probability. Students below a 7.5 CGPA face a significantly lower "floor" for Ivy League chances regardless of GRE scores.Feature Importance: GRE and TOEFL scores are highly correlated ($r > 0.8$). For future data collection, focusing on one high-quality standardized test score may suffice.Research Premium: Having research experience increases the "Chance of Admit" by approximately 3-5% on average, holding all other scores constant.
