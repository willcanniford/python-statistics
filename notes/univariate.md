# Univariate data   
The median is more robust than the mean and isn't as sensitive to outliers. If the data tails off to the left, then the data distribution is left-skewed and the mean is going to be less than the median; this highlights the sensitivity that the mean has to those outliers that are lower in value as they drag the mean average down and to the left of the median.  

The standard deviation is roughly the average distance of observations from the mean.  

The range is less robust to outliers, and in this case you are probably better off using the  IQR to return the distribution as that will tell you where most of the data falls. 

## Empirical Rule 
For bell-shaped distirbutions, we can follow the 68-95-99.7 rule. This is the expected percentage of the population that will fall within 1-2-3 standard deviations from the mean of the population. 

You can work out the standard score of an observation, that tells you the number of standard deviations you are away from the mean. i.e. with a mean of 10 and a standard deviation of 4, an observation of 15 would have a standard score (z-score) of 15-10/4 = 1.25