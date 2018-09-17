# 31st place solution at Home Credit Default Risk competition
![alt text](https://storage.googleapis.com/kaggle-media/competitions/home-credit/about-us-home-credit.jpg)

Description
=============

Home Credit Default Risk was the biggest Kaggle competition ever. It lasted for 3 months and 7198 teams took a part.
\nSome details https://www.kaggle.com/c/home-credit-default-risk/discussion/66010

Result
---------------------

I took 31st place (top 1%).

Solution
---------------------

My model is a stack of 4 models by logistic regression:

- open solution with seed 0 from https://github.com/neptune-ml/open-solution-home-credit
- open solution with seed 90210 from https://github.com/neptune-ml/open-solution-home-credit
- kaggle kernel https://www.kaggle.com/aantonova/797-lgbm-and-bayesian-optimization
- my own XGBOOST model
