# Learning Objectives

The learning objectives for this week are closely related to those of
the previous week

## Conceptual


After this week you should be able to:

* Define the term *sample* and *population*
* Understand the difference between sampling with and without replacement

* Define the sampling distribution of a statistic (such as the sample mean or proportion)
* Explain how the standard error depends on sample size n
* Understand that the sampling distribution of the mean can be
obtained in several ways including:
    * Calculated empirically from the population - draw many samples of size nfrom the population and plot their means - only possible if the
population distribution is available (rarely possible outside
exercises)
    * Estimated using a known distribution (Normal if central limit
theorem applies, t if data distribution is normal)
    * Calculated empirically from the sample by resampling (bootstrapping)

* Define a confidence interval and understand its relationship to
the sampling distribution of the mean




This material is covered in the lecture and recapped in the worked
examples in Python

## Python skills

This week there is an emphasis on simulating the process of drawing a
large number of (re)samples from a sample distribution

The key skill practiced this week is building a `for` loop to
repeat a process many times
(such as drawing a random sample and getting its mean)

You might need to change some variable (such as sample
size n) on each pass through the loop.

Additional new(ish) Python skills:

* Plot an expected distribution such as a curve from the function `stats.norm.pdf()` over a histogram of simulated data
* Plot a Q-Q plot
* sample from `numpy` array or a `pandas` dataframe
using `numpy.random.choice()` and `pandas.df.sample()<` respectively

This material is covered in the Jupyter Notebooks in this section
