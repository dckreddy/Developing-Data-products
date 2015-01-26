---
title       : Developing Data Products - Course Project
subtitle    : 
author      : Chaitanya Duvvuru
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [mathjax]            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Uniform Distribution presentation


This presentation 

1. Gives an overview of Uniform Distribution.

2. Explains probability Distribution function with a mathematical fomula.

3. provides R code commands for Uniform Distribution.

--- .class #id 

## Math Formulae


1. Uniform distribution random variable is the form $U(a,b)$

2. Probability Distribution Function  is $f(x)=\frac{1}{b-a}$ for a <= x <= b;
                                                            0 for x < a or x > b

--- .class #id 

## R code


The probability is calculated using R function punif()


```r
u <- runif(10) 
punif(u)
```

```
##  [1] 0.40130428 0.56691864 0.61840277 0.78665837 0.35761677 0.29840181
##  [7] 0.07309905 0.11674883 0.75142923 0.64721125
```


--- .class #id 

## References


1. http://astrostatistics.psu.edu/su07/R/html/stats/html/Uniform.html

2. http://slidify.org/start.html

3. http://slidify.org/samples/

--- .class #id 

## Thank you!


 This is the last slide. Hope you enjoyed this App. 
