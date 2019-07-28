## Linear Regression

#### Assumptions for Linear Reqression
- The mean of the response at each value of the predictor is a linear function of the preditor
- the errors are independent
- the error at each value of the predictor are Normally distributed
- the error at each value of the predictor have the equal variance

#### Theorm 
1. Parameter estimation: After have the veriables defined and sample selected, we find the parameters by looking for the "least squares estimates", which minimize the sum of the squared prediction errors.
2. Model ilustration & evualation: 
- the variance of estimated mean of response, $\sigma^2$ : how much the responses (y) vary around the (unknown) mean population regression line. We estimate is by sample variance, mean square error, the common variance of the many subpopulations

- coefficient of determination or r-squared value: the r. We can interpret r-square by egression sum of squares divided by the total sum of squares. We can interpret r-square by saying "r2 ×100 percent of the variation in y is 'explained by' the variation in predictor x". However r-square doesn't tells the model of fit.

- the hypothesis test for the population correlation ρ to learn of a linear association between two variable. t-test or ANOVA F- test for testing the population correlation coefficient H0: ρ = 0.

#### Why we need to make those assumptions
1.  The mean of the response at each value of the predictor is a linear function of the preditor
2. Why errors should be normally distributed?
- The methods used for parameter estimation (MLE) can also imply the assumption of normally distributed random errors. 
  This assumption is requered to make sure that the ordinary least squares estimators are unbiased.
