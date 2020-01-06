[Think Stats Chapter 4 Exercise 2](http://greenteapress.com/thinkstats2/html/thinkstats2005.html#toc41) (a random distribution)

```{python}
randomdist = np.random.random(1000)
#pmf
thinkplot.Pmf(randomdist)

#cdf
cdf = thinkstats2.Cdf(randomdist)
thinkplot.Cdf(cdf)
```
