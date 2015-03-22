Uniform Distribution Overview
========================================================
author: Chaitanya Duvvuru
date: 3/22/2015

Uniform Distribution presentation
========================================================

This presentation 

- Gives an overview of Uniform Distribution.

- Explains probability Distribution function with a mathematical fomula.

- provides R code commands for Uniform Distribution.

Uniform Distribution Math Formulae
========================================================

1. Uniform distribution random variable is the form $U(a,b)$

2. Probability Distribution Function  is $f(x)=\frac{1}{b-a}$ for a <= x <= b;
                                                            0 for x < a or x > b
                                                            

Uniform Distribution with R 
========================================================


```r
u <- runif(10) 
punif(u)
```

```
 [1] 0.5727854 0.2456371 0.6737064 0.3875779 0.6008992 0.4612766 0.3530536
 [8] 0.9693516 0.8749484 0.8073898
```

References
========================================================

1. http://astrostatistics.psu.edu/su07/R/html/stats/html/Uniform.html

2. http://slidify.org/start.html

3. http://slidify.org/samples/

