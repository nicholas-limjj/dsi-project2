# Using Ames Housing Dataset to Predict Prices of Houses

## Executive Summary

### Contents:
- [Useful Links](#Useful Links)
- [Recommendations](#Recommendations)
- [Conclusions](#Conclusions)

## Useful Links
Link to data documentation: http://jse.amstat.org/v19n3/decock/DataDocumentation.txt
Link to Kaggle Regression Challenge: https://www.kaggle.com/c/dsi-us-6-project-2-regression-challenge


## Recommendations
Using model 2 where we used the top 20 features found, applying polynomial features on them, and get the top 20 from it again.

## Conclusions
From the above 2 models, even though we observe a good improvement in score for the public score in model 2, the private score remains almost consistent across the 2 models, which sort of indicates a slight overfitting in the model itself. But model 2 still shows to be a better predictor as compared to model 1 since the RMSE for the private scores remain fairly consistent for the private scores but improves for the public ones.

The way we clean our data may also impact our feature selection as well, so further experiments on the cleaning process can be done. For example, instead of replacing null values with default NAs or 0, we can try finding the mean/mode/median of the feature and replace those null values with it instead.
