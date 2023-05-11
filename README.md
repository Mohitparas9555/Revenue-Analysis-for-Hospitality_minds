# Revenue-Analysis-for-Hosptality_minds
Enhancing revenue via lead qualification (Pyspark)















Performed Exploratory Data Analysis (EDA) 



Identifying The count of maximum hotels booked According to the type of Hotel
Analyzing the count of guests per month for "Villa" And "Motel" Types of Hotel
Analyzing the count of different types of Reserved rooms as per each hotel type
how many previous bookings were not canceled per year in each hotel
conducting the Null hypothesis testing
Applied Pre-Processing


Conducting T-Test



Convert categorical variables into numerical features using StringIndexer


The t-test is a statistical hypothesis test used to determine if there is a significant difference between the means of two groups. 

It calculates the t-statistic, which measures the difference between the means relative to the variation in the data.

In this case, our calculated t-test statistic is 8.079298389670557 which means that there is a significant difference between the means of the two groups that you are comparing. The significance level of the t-test is determined by the p-value. 

﻿A p-value less than the significance level (usually 0.05) indicates that the difference between the means is statistically significant, while a p-value greater than the significance level indicates that the difference is not statistically significant.

It is important to note that the interpretation of the t-test depends on the context and the specific research question being investigated





Performed CHI-SQUARE Test 



The result of the chi-squared test is a vector of p-values for each feature in the dataset.

In this case, the result is a DenseVector with 10 p-values. Each p-value represents the statistical significance of the association between a feature and the target variable (in this case, cancellation).

A p-value is the probability of observing a test statistic as extreme as the one computed from the data, assuming the null hypothesis is true. In this case, the null hypothesis is that there is no association between the feature and the target variable.

A low p-value (typically less than 0.05) indicates that there is strong evidence to reject the null hypothesis and conclude that there is a significant association between the feature and the target variable.

Therefore, in your result, all the p-values are 0.0, which means there is strong evidence to reject the null hypothesis for all the features and conclude that they are significantly associated with the cancellation variable.



This implies that the alternate hypothesis testing is positive
