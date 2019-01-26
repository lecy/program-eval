# Chapter Files 

Add your RMD and rendered HTML files here. 

Images should go in the "assets" folder.

Name the master power point deck *IMAGES.pptx*. 

# Book Organization


## Part I: Regression

1. Case Study - Classroom Size
2. Regression Basics 
   1. regression formula 
   1. model fit 
     1. residuals 
3. Ballentine Venn Diagrams 
  - variance of Y
  - partitioning dv into y-hat, resid
  - variance explained (R2)
  - control variables
4. Program Impact
  - input / outcomes machine
  - effect size (beta*std)
  - standardized coefficients
5. Hypothesis Testing
  - confidence intervals / coefficient plots 
  - slopes (null hypothesis)
  - dummy variables (null hypothesis)
  - interactions (slope*treat_dummy)
  - interactions (treat_dummy*time_dummy)
  - type i & ii errors 
6. Control Variables
  - good controls
  - bad controls (multicollinearity)
  - power
  - competing hypotheses framework
  - partitioned regression
7. Omitted Variable Bias
8. Seven Sins of Regression
  - omitted variable bias
  - selection
  - group bias (heterogeneity)
  - multicollinearity
  - measurement error
  - specification bias
  - outliers
9. Transformations
  - liniear transformations
  - quadratic models
  - log models
10. Improving Standard Errors
  - robust standard errors
  - bootstrapping
  - clustering
11. Model Diagnostics
  - outliers
  - comparing 2 models


## Part II: Research Design

**Intro / Overview**  
1.	Introduction to research design    
2.	Testing the Program Hypothesis   
  -	Treatment groups (ANOVA, t-test, regression with dummies) 
  -	Treatment levels (regression) 
  -	Treatment categories (chi-square) 
4.	Validity (moved reliability to end) 
  - Internal 
  - External 
  - Type I and Type II Errors 
5.	Power 
  - Sample size  
  - Measurement error in DV and IV  
6.	Threats to Internal Validity  
  - Sample design  
    - Selection in (unobserved heterogeneity, omitted variable bias) 
    - Selection out (attrition)  
  - Trends in the data 
    - Maturation 
    - Secular trends 
    - Seasonality 
    - Regression to the mean 
    - Testing effects / Hawthorn effects 
  - Study calibration 
    - Study time-frame  
    - 	Measurement error 
  - Contamination 
    - Intervening effects 
    - Diffusion of treatment 


**Counterfactual Analysis**
7.	The three counterfactuals 
  - Pre-post with control (difference-in-difference) 
    - Can test for equivalence of groups before treatment 
    - Can test for secular trends 
    - Can estimate the counterfactual 
    - 	Can test for treatment effects 
  - Post-test only (requires equivalent groups to be valid) 
  - Pre-post reflexive (requires absence of trends) 
8.	Construction of a counterfactual 
  - Equivalent groups 
    - RCT 
    - Matching 
      - Observable versus non-observable heterogeneity  
    - Reflexive design  
    - Test for equivalence (comparison of sample means, bonferoni corrections) 
      - In reflexive design, test would be for non-random attrition 
  - Non-equivalent groups  
    - What can we say in this case?
    ii.	Use of difference-in-difference with non-equivalent groups
      1.	Parallel lines assumption need to construct a valid counterfactual
    iii.	Using comparison group to create upper or lower bounds
      1.	Use of bias formula to determine direction of bias
9.	Treatment fidelity 
  - Intention to treat estimate 
  - Treatment-on-treated estimate 
  - Challenges with diffusion of treatment, individuals switching groups 
10.	Attrition 
  - Random attrition – impacts power, not bias (leads to type ii errors) 
  - Non-random attrition – introduces bias 
  - Tests for each 
    - Comparison of study group means after attrition 
    - Comparison of those that leave across groups 
    - Comparison of leavers and stayers within groups 
    - Comparison of rates of attrition across groups 
 
**Research Design**  
11.	Experimental methods  
  a.	Randomization / true control groups  
  b.	Limitations (ethics, can’t randomize gender, etc.)  
  c.	Challenges to implementation  
12.	Natural experiments (external events that act like experiments)  
  a.	Lotteries  
  b.	Stages roll-out of policies  
  c.	Earthquakes, policy change, etc.  
13.	Non-experimental methods  
  d.	Observational  
  e.	Naturalistic  
14.	Quasi-experiments  
  a.	Post-test only  
    i.	Requires equivalent comparison groups  
    ii.	Propensity score matching   
    iii.	Regression discontinuity models (summer school example)  
  b.	Reflexive Studies   
    i.	Requires arguments or tests for absence of trend (no gains independent of treatment)  
    ii.	Interrupted time-series models  
  c.	Pre-post with comparison  
    i.	Difference-in-difference models  
    ii.	Interrupted time-series with comparison group  
15.	Advanced experimental design  

**Data Collection**
16.	Reliability 
17.	Measurement Error
18.	Surveys
19.	Interview methods
20.	Coding Systems


## Part III: Causal Models

1. Review of OVB Problem
2. Instrumental Variables
3. Interrupted Time Series
4. Difference-in-Difference
5. Fixed Effects
6. Binary Outcome Models
  - linear prob model
  - logistic regression
7. Propensity Score Matching
8. Regression Discontinuity Design
9. Duration Analysis
  - discrete-time failure models
10. Categorizing Models by Counterfactual
  - Post-Test Only
    * instrumental variables
    * matching
    * regression discontinuity
  - Reflexive
    * interrupted time series
    * fixed effects models
  - Pre-Post w Control
    * diff-in-diff
10. Fixing Standard Errors
  - weighted standard errors
  - clustering
  - autocorrelation
  - limited dependent variables
11. Case Studies
  - compare estimates across models
  - Marriage and happiness
    - fixed effect
    - time-series
    - diff-in-diff
  - Gender pay gap
    - OLS 
    - matching
    - diff-in-diff

