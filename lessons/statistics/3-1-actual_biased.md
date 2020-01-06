[Think Stats Chapter 3 Exercise 1](http://greenteapress.com/thinkstats2/html/thinkstats2004.html#toc31) (actual vs. biased)

```{python}
exercise = thinkstats2.Pmf(resp.numkdhh, label='numkdhh')

#actual
thinkplot.Pmf(exercise)
pmf.Mean()

#biased
biased = BiasPmf(exercise, label='biased')
thinkplot.Pmf(biased)
biased.Mean()
```
