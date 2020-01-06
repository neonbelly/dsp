[Think Stats Chapter 5 Exercise 1](http://greenteapress.com/thinkstats2/html/thinkstats2006.html#toc50) (blue men)

```{python}
import scipy.stats
dist = scipy.stats.norm(loc=178, scale=7.7)
#number of ppl btw 5'10 and 6'1
dist.cdf(185.4) - dist.cdf(177.8)
```
