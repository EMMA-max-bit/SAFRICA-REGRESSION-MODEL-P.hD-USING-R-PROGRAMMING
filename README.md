# SAFRICA-REGRESSION-MODEL-P.hD-USING-R-PROGRAMMING
This exercise employs a sample from a 1994 survey of South African workers. The data are contained in a ﬁle called safrica.dta

## INTERPRETATION TO QUESTION 2
## A. plausibility of Regression Assumptions
1. Variation in X: There is adequate variation in the independent variable-that is, the percent
of years for leftist government control, or percleft-across the 12 countries. This ensures
the model can meaningfully estimate the eﬀect of ideology on unemployment. 

2. Linearity in Parameters: The association between government ideology and
unemployment is approximately linear. The scarterplot indicates that a straight-line ﬁt is
appropriate because there is no apparent major curvature or non-linear trends. 

3. Random Sampling: Each observation (country) is an independent case. Although this is
cross-national data rather than a true random sample, there are no repeated measures
and the observations are independent. 

4. Zero Conditional Mean: We have no evidence that important explanatory variables are
   left out or that the residuals are systematically related to percleft. So, our expectation of
the error term conditional on percleft is zero: 

5. Homoskedasticity: There is constant variance of residuals across fittd values. Of course,
the small sample size here of 12 countries may show some slight variation, but no major
evidence of heteroskedasticity can be seen. 
 
6. Normality: Since there are only 12 observations, it cannot be considered completely
normal, but it seems that the residuals are fairly symmetric without extreme outliers. So
normality assumption is reasonably met. 

## B. Plausibility of Regression Assumption
1. Variation in X: There is sufficient variation in the independent variable, which is the
percentage of years under leftist government control, across the 12 countries to estimate
the magnitude of its eﬀect on inﬂation. 
 
2. Linearity in Parameters: The scarter plot shows that government ideology and inﬂation
are related in an approximately linear way. The model speciﬁcation is linear in parameters,
hence appropriately catches the trend. 

3. Random Sampling: Each of the observations is a diﬀerent country, considered an
independent case. Even though the data are cross-national rather than being a random
sample, there are no dependencies or repeated measures that violate this assumption. 

4. Zero Conditional Mean: There is no strong evidence that omitted variables are
systematically correlated with percleft, and residuals do not display a patern. Thus, the
expected error term conditional on percleft is approximately zero.


5. Homoskedasticity: The residuals have a seemingly constant variance for all fitted values.
There is no sign of increasing or decreasing spread (funnel shape), which would mean that
homoskedasticity holds.

6.  Normality: The residuals are approximately symmetric and fairly normal. While the small
sample size may lead to some minor deviations, the normality assumption holds fairly well.
