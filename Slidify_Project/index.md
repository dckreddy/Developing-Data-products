---
title       : Developing Data Products - Course Project
subtitle    : 
author      : 
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [mathjax]            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

### My Shiny App project: Uniform Distribution App

1.The app is built using shiny and hosted on shinyapps.io.

2.Basicly the app calculates probability of a score according to standard normal density.

--- .class #id 

### Math Formulae
1. Uniform distribution random variable is the form $U(a,b)$
2. Probability Distribution Function  is $f(x)=\frac{1}{b-a}$ for a <= x <= b;
                                                            0 for x < a or x > b

--- .class #id 

### R code

The probability is calculated using R function punif()


```r
x = 0.5
lower = T
pnorm(x, mean = 0, sd = 1, lower.tail = lower)
```

```
## [1] 0.6914625
```

The value for x and wether user wants a lower probability or a upper probability are based on user input.

--- .class #id 

### References
1. http://astrostatistics.psu.edu/su07/R/html/stats/html/Uniform.html

--- .class #id 

### Thank you!

This is the last slide. Hope you enjoyed this App. 
