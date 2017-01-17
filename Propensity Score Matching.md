## Project description 

### Data 


### Goal
To reduce the "selection bias" among groups.


### Challenge
1. Multiple groups: Six-group comparison, instead of two. 
2. Covariate selection: A long list of potential covariates (theorety driven decision) 
3. Most are categorical variables 
4: Sample size variates across groups 

### Strategy 


## Method description 
Propensity Score Matching (PSM) is 



## Implementation 

### Process
1. Data cleaning

2. Calcualte the propensity score 

Neither package supports mulltinomial logistic regression. 

The "nnet" package support multinomial logistic regression, providing the  



### Tool
Software: R

Package 1: MatchIt 
+: provide the matched sample after matching for secondary analysis 
-: the balance evaluation is less strigent 


Package 2: Matching
+: support more 
-: could not find a function that output the matched sample for futher analysis 


