# Income Level Insights: A Data-Driven Approach to Economic Census Analysis

## Introduction

This project leverages economic census data to categorize American individuals into income brackets of <=$50K and >$50K. It aims to highlight economic disparities and support informed decision-making for businesses and policymakers.

## Dataset

The project utilizes the 1994 UCI economic census data, a comprehensive dataset reflecting the socio-economic aspects of the U.S. population, including demographics, education, employment, and income.

## Methodology

Our approach involves:

- Detailed data examination to identify key variables like age, education, occupation, and capital gains.
- Comprehensive data cleaning, addressing over 6000 unclear data points.
- Exploratory Data Analysis (EDA) and application of machine learning techniques, with a focus on the Random Forest model.
- Feature engineering and one-hot encoding for categorical variables.
- Evaluation of algorithms based on accuracy, precision, recall, and interpretability, with Random Forest emerging as the optimal choice.
- Use of GridSearchCV for model refinement and a confusion matrix for model evaluation.

## Key Findings

The Random Forest model achieved an accuracy of approximately 85.88%, with 'fnlwgt', 'age', and 'education-num' being the most influential factors.
The model provides a nuanced understanding of income disparities, highlighting the importance of socioeconomic factors in income distribution.

## Applications and Impact

For businesses: Enhances marketing strategies, location planning, and product offerings.
For policymakers: Informs welfare policies, educational grants, and infrastructure development.

## Future Work

Incorporating more up-to-date economic data.
Exploring advanced machine learning techniques like Gradient Boosting and Neural Networks.
Integrating additional variables, focusing on local economic indicators.
Regular model updates and validation to adapt to changing economic trends.

## Conclusion

This project presents a model that not only accurately classifies income levels but also offers deep insights into the dynamics of income distribution, holding significant potential for societal impact.
