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
 [1] 0.77915703 0.37499327 0.84681902 0.55495750 0.62036374 0.70762066
 [7] 0.12077943 0.01397822 0.21533427 0.45118973
```

References
========================================================

1. http://astrostatistics.psu.edu/su07/R/html/stats/html/Uniform.html

2. http://slidify.org/start.html

3. http://slidify.org/samples/

