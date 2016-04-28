---
title: "SoySdTrtLogisticProb"
author: "Devon"
date: "April 28, 2016"
output: html_document
---


```
## 
## 
## processing file: Probability.Rmd
```

```
##   |                                                                         |                                                                 |   0%  |                                                                         |......................                                           |  33%
##   ordinary text without R code
## 
##   |                                                                         |...........................................                      |  67%
## label: unnamed-chunk-16 (with options) 
## List of 1
##  $ echo: logi FALSE
```

```
##   |                                                                         |.................................................................| 100%
##   ordinary text without R code
```

```
## output file: Probability.md
```

```
## [1] "Probability.md"
```

![plot of chunk unnamed-chunk-15](figure/unnamed-chunk-15-1.png)

```
## Warning in optwrap(optimizer, devfun, start, rho$lower, control =
## control, : convergence code 1 from bobyqa: bobyqa -- maximum number of
## function evaluations exceeded
```

```
## Warning in checkConv(attr(opt, "derivs"), opt$par, ctrl = control
## $checkConv, : Model failed to converge with max|grad| = 0.0054611 (tol =
## 0.001, component 1)
```

```
## 
## Call:
## glm(formula = N ~ soycost + location + Low5wk + sdtrt + var, 
##     family = "binomial", data = results$data)
## 
## Deviance Residuals: 
##     Min       1Q   Median       3Q      Max  
## -2.0787  -0.8176  -0.4550   0.9438   2.4796  
## 
## Coefficients:
##             Estimate Std. Error z value Pr(>|z|)    
## (Intercept) 22.80994    3.43409   6.642 3.09e-11 ***
## soycost      0.06507    0.02945   2.209 0.027157 *  
## locationHIL -1.29463    0.35938  -3.602 0.000315 ***
## locationIN2 -0.81626    0.35704  -2.286 0.022245 *  
## locationLEN -1.45815    0.37279  -3.911 9.18e-05 ***
## locationSAG -3.67528    0.50013  -7.349 2.00e-13 ***
## locationSAN -3.19668    0.46125  -6.930 4.19e-12 ***
## locationSTJ -2.57859    0.46223  -5.579 2.43e-08 ***
## Low5wk      -0.38289    0.05880  -6.512 7.42e-11 ***
## sdtrtF+I     0.07766    0.22757   0.341 0.732909    
## sdtrtF+I+N  -0.78673    0.24093  -3.265 0.001093 ** 
## var2        -1.96630    0.29775  -6.604 4.01e-11 ***
## var3        -0.42441    0.26857  -1.580 0.114050    
## var4        -0.91865    0.27691  -3.318 0.000908 ***
## var5        -0.23867    0.47854  -0.499 0.617960    
## var6        -0.41975    0.48385  -0.868 0.385653    
## ---
## Signif. codes:  0 '***' 0.001 '**' 0.01 '*' 0.05 '.' 0.1 ' ' 1
## 
## (Dispersion parameter for binomial family taken to be 1)
## 
##     Null deviance: 826.92  on 629  degrees of freedom
## Residual deviance: 651.49  on 614  degrees of freedom
## AIC: 683.49
## 
## Number of Fisher Scoring iterations: 5
```

```
## [1] 0.4463935
```

![plot of chunk unnamed-chunk-15](figure/unnamed-chunk-15-2.png)

```
## [1] "23" "27" "29"
```

```
## Warning: non-unique values when setting 'row.names': '2013 ALE', '2013
## HIL', '2013 IN2', '2013 LEN', '2013 SAG', '2013 SAN', '2013 STJ', '2014
## ALE', '2014 HIL', '2014 IN2', '2014 LEN', '2014 SAG', '2014 SAN', '2014
## STJ', '2015 ALE', '2015 HIL', '2015 IN2', '2015 LEN', '2015 SAG', '2015
## SAN', '2015 STJ'
```

```
## Error in `row.names<-.data.frame`(`*tmp*`, value = value): duplicate 'row.names' are not allowed
```

![plot of chunk unnamed-chunk-15](figure/unnamed-chunk-15-3.png)

