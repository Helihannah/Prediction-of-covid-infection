# Prediction-of-covid-infection

In this project, I try to build four models, having vaccinated covariate or not, and linear or polynomial, to compare the model performance based on covid data and predict future covid infection.

I found out that the model would have better performance when considering the vaccinated covariate, which means we can not neglect the impact of the number of people vaccinated on the model, no matter for linear or polynomial.

Compared with the linear model, the polynomial model always behaves better on training data, but worse on testing data. This is because overfitting has occurred.

Therefore, the best model to predict covid severity should be a linear regression model having the vaccinated covariate so far. To further improve this model, maybe I should consider more covariates to get better performance on test data, such as the age profile.
