## Probability Theory

- Probability
- Bayes'Theorem


## Distribution
#### Discrete Distribution
#### Continuous Distribution
- Binomial Distribution
- Pisson Distribution
- Normal Distribution
#### Birvariate Distribution
- Birvariate normal distirbution
#### Distribution of function of random variables
- Central Limit Theorem: random sample from a distribution, if the sample size is 'sufficiently large' then the sample mean follows an approximate normal distribution. 
- The use CLT: we can use normal distribution to discribe or estimate the  sample mean of a data sample
 - Normal Approximation to Binomial
 - Normal Approximation to Poisson
 

## Estimation
#### Point Estimation & Confidence Interval
- Maximum likelihood estimation
a method of estimating the parametor which maximizes the probability or the likelihood of getting the data we observed.
- Unbaised estimator 
- Confidence interval
reference link: https://statisticsbyjim.com/hypothesis-testing/hypothesis-tests-confidence-intervals-levels/
https://statisticsbyjim.com/hypothesis-testing/confidence-prediction-tolerance-intervals/
https://newonlinecourses.science.psu.edu/stat414/node/199/
 for a random smaple from a normal distibution, the (1-&alpha)% confidence interval for the mean

$$(x-z_{\alpha/2}(\sigma/\sqrt{n}), x+z_{\alpha/2}(\sigma/\sqrt{n}))$$

confidence interval always lines with the significant level.
- A confidence level determines the distance between the sample mean and the confidence limits.
- A significance level determines the distance between the sample mean and the critical regions.

the confidence interval and confidence level:
a learge condidence level will lead to a wider confidence interval.
Because you expected a higher percentage of value fall into the confidence interval, which required a wider range to cover a more value.

Diffrence between prediction interval and confidence interval:
The prediction interval will take the MSE intp account. Always has a wider range than the cofidence interval.
https://rpubs.com/aaronsc32/regression-confidence-prediction-intervals
