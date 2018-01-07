[Think Stats Chapter 4 Exercise 2](http://greenteapress.com/thinkstats2/html/thinkstats2005.html#toc41) (a random distribution)

rnums = np.random.random(1000)

pmf = thinkstats2.Pmf(rnums)

thinkplot.Pmf(pmf, linewidth = 0.1)

thinkplot.Config(xlabel = 'Random Num', ylabel = 'PMF')

cdf = thinkstats.Cdf(rnums)

thinkplot.Cdf(cdf)

thinkplot.Config(xlabel = 'Random Num', ylabel = 'CDF')

Since the CDF is close to being a straight line, we can assume that the distribution is uniform. 10% of the data is below the 10th percentile, 20% of the data is below the 20th percentile etc.
