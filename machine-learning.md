
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

- influential points
outlier / leverage 
outliner-extreme y value
leverage-extrame x balue

standardized residuals to determine outliners
studentized residuals-delete the observations one at a time, each time fitting the regression model on remaining n-1 obervations
Difference in fits (DFFITS)-the difference in fits quantifies the number of standard deviations that the fitted value changes when the ith data point is omitted.
cook's distance-Cook's Di depends on both the residual, ei (in the first term), and the leverage, hii (in the second term). That is, both the x value and the y value of the data point play a role in the calculation of Cook's distance.

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
- Bagging
- Random Forests
- Boosting

## Support Vector Machine
#### Theory
- Maximal Margin Classifer: calssification using a separating hyperplane by choosing the maximal margin hyperlane; the maximal margin hyperlane depends directly on only a small subset of the observations
- support vector classifier (soft margin classifier): the generalization of the maximal margin classifier to the non-seperable case
  Allow obeservation on the incoorect sided of the margain or hyperlane to better classification of most of the training observation. The observations that lies directly on the margin or on the wrong side of the margin for their class are support vectors. And only support vectors affect the classifier is in line with oir previous assertion that C controls the bias-variance trade-off of the support vector classifier. 
   - Width of Margin M: we wanna maximize this number
   - Slack variable e1, ..., en: where the ith observation is located, relativeto the hyperplane and relative to the margin
   - Nonnegative tuning parameter C: nounds the sum of the e, it determines the number and serverity of the violations to the margin
- Support Vector Machine (SVM): enlarging the feature space in a specfic way by using kernels. 
   - Logic: inner product between the new point x and each of the training points xi.
   - Kernel: a function that quantifies the similarity of two observations. eg. linear kernel quantifies the similarity of a pair of observations user Pearson correlation. Polynomial kernel of degree d, which lease to a much more flexiable decision boundary. Radial kernel.
- classification for K > 2, more than 2 classes: one-verse-one classification, one-verse-all classification
- Relationship to logistic regression
