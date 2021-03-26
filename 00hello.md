hello
================
nobuo
2021/3/22

This is a paragraph in an R Markdown document.

Below is a code chunk:

``` r
fit = lm(dist ~ speed, data = cars)
b   = coef(fit)
plot(cars)
abline(fit)
```

![](00hello_files/figure-gfm/unnamed-chunk-1-1.png)<!-- -->

The slope of the regression is 3.9324088.
