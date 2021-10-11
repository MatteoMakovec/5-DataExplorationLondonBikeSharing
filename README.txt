Timestamps aren't useful in their format, but have to be decomposed in their inner variables (year, month, day, etc...) in order to be used.

We can see how important is properly clean data.
The professor, after be sure that the whether was checked hourly, erase the column minutes (since it carries only zeroes).
Furthermore, the processor erase the column timestamp too since its information were already extrapolated in the columns (weekday, year, month, hour).

We can see that the professor, in the data exploration phase, usually uses data visualization as a useful tool to spot good patterns.
Therefore a very important thing is to be able to read every type of plot.

After the preprocessing phase, we create the linear model and we resolve it normally, with the lasso regularization, with the svm (support vector machines), with the k-neighbors regression and with the random forest regression.
How can I compare the different results?