
## Linear Regression

#### Assumptions for Linear Reqression
- The mean of the response at each value of the predictor is a linear function of the preditor
- the errors are independent
- the error at each value of the predictor are Normally distributed
- the error at each value of the predictor have the equal variance

#### Theory 
1. Parameter estimation: After have the veriables defined and sample selected, we find the parameters by looking for the "least squares estimates", which minimize the sum of the squared prediction errors.
2. Model ilustration & evualation: 
- the variance of estimated mean of response, $\sigma^2$ : how much the responses (y) vary around the (unknown) mean population regression line. We estimate is by sample variance, mean square error, the common variance of the many subpopulations

- coefficient of determination or r-squared value: the r. We can interpret r-square by egression sum of squares divided by the total sum of squares. We can interpret r-square by saying "r2 ×100 percent of the variation in y is 'explained by' the variation in predictor x". However r-square doesn't tells the model of fit.

- the hypothesis test for the population correlation ρ to learn of a linear association between two variable: 
  - t-test for testing the population correlation coefficient H0: ρ = 0:
  - ANOVA F- test for testing the population correlation coefficient H0: ρ = 0:
Break down the total variation in y ("total sum of squares") into two components:
a component that is "due to" the change in x ("regression sum of squares")
a component that is just due to random error ("error sum of squares")
If the regression sum of squares is a "large" component of the total sum of squares, it suggests that there is a linear association between the predictor x and the response y.

#### Why we need to make those assumptions
1.  The mean of the response at each value of the predictor is a linear function of the preditor
2.  Why errors should be normally distributed?
Good reference:
[WHy is the error term normally distributed](https://www.quora.com/Why-is-the-error-term-normally-distributed)
- Based on the Centrel Limited Theorm:as the number of these error gets larger, the distribution of the error term tends to approach the normal distribution 
- The methods used for parameter estimation (MLE) can also imply the assumption of normally distributed random errors. 
  This assumption is requered to make sure that the ordinary least squares estimators are unbiased, at which step we assume the expection of mean of error is zero.
- When do model evaluation and testing the corelation between variable and response, t-test and F- test are not applicable unless the error term is normal distributed.

## Logistic Regression

## Tree Based Model

#### Regression Tree
#### Classification Tree
#### Bagging, Random Forests, Boosting
-Bagging
- Random Forests
- Boosting

## Support Vector Machine
#### Theory
- Maximal Margin Classifer: calssification using a separating hyperplane by choosing the maximal margin hyperlane; the maximal margin hyperlane depends directly on only a small subset of the observations
- support vector classifier (soft margin classifier): the generalization of the maximal margin classifier to the non-seperable case
  Allow obeservation on the incoorect sided of the margain or hyperlane to better classification of most of the training observation
  
