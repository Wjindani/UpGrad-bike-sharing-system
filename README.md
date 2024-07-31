# Multiple Linear Regression Bike Sharing Assignment

> An analysis to predict the demand for shared bikes using multiple linear regression.

## Table of Contents

- [General Information](#general-information)
- [Technologies Used](#technologies-used)
- [Conclusions](#conclusions)
- [Acknowledgements](#acknowledgements)

## General Information

- This project aims to predict the demand for shared bikes based on various independent variables.
- **Background**: A US bike-sharing provider BoomBikes has experienced significant revenue dips due to the ongoing Corona pandemic. Understanding the demand for shared bikes is crucial for the company to prepare and strategize for the post-pandemic scenario.
- **Business Problem**: The company wants to identify significant factors affecting bike demand and how well these variables describe the demand patterns.
- **Dataset**: The dataset includes variables like weather, season, and user information over a period.

## Conclusions

- The most significant features for predicting bike demand include:
  - Year (`yr`)
  - Spring season (`season_spring`)
  - July (`mnth_jul`)
  - Winter season (`season_winter`)
  - September (`mnth_sept`)
  - Holiday (`weekday_sun`)
  - Good weather situation (`weathersit_good`)
  - Moderate weather situation (`weathersit_moderate`)
  - Temperature (`temp`)
- The model explains approximately 83% of the variance in the training data and 82% in the test data, indicating good generalization to unseen data.
- These insights help BoomBikes understand the demand patterns for shared bikes and adjust their business strategies to cater to people's needs and improve revenues post-pandemic.

## Technologies Used

- Python - version 3.8
- NumPy - version 1.19
- pandas - version 1.1
- Matplotlib - version 3.3
- Seaborn - version 0.11
- Scikit-learn - version 0.23
- Statsmodels - version 0.11

## Acknowledgements

- This project was inspired by the need to understand bike-sharing patterns and improve business strategies post-pandemic.
- The dataset was provided as part of a data science assignment.
- The project was based on multiple linear regression analysis techniques.

## Contact

Created by [@Wjindani] - feel free to contact me!
