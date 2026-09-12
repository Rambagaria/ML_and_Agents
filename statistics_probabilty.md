Normal/ Gaussian/ bell Curve - centred around average value. Width of curves more, means std deviation more. eg. height, weight, commute time.

Std Deviation - 68%, 95%, 99.7 (Emperical rule)

Central Limit Theorem - the distribution of sample means (A sample size of n ≥ 30 is generally large enough for the theorem to work) approaches a normal distribution as the sample size gets larger, no matter what the original population distribution looks like whether it is skewed or uniform.

Not possible to calculate "POPULATION" Mean (mu), so we approximate using "SAMPLE" mean (x bar). More data gets us closer to "POPULATION" Mean. 

Bessel's correction - statistical method used when calculating the variance of a sample to provide a more accurate, unbiased estimate of the population's true variance. Like dividing by n-1 instead of n.

Binomial Distribution and Test - statistical model where two outcomes are equally likely. eg. orange vs grape fanta (https://www.youtube.com/watch?v=J8jNoF-K8E8) 

In the context of the binomial distribution, the null hypothesis is the assumption that there is no real preference or bias between two possible outcome. The most commonly used threshold to reject the null hypothesis is 0.05. If the calculated p-value is less than or equal to this threshold, the results are typically considered statistically significant, meaning the null hypothesis is rejected.

Contigency Table -  It organizes raw data into a grid format consisting of rows and columns, making it easier to analyze the distribution of a population across different groups. For example, if we are tracking people who love candy versus those who love soda, the table allows us to see the exact counts for every combination, such as those who love both, neither, or only one of the two options.

A conditional probability is the probability of an event occurring, given that another specific event has already occurred

Bayes Theorem - P(A|B) = P(B|A) * P(A) / P(B)

Posterior is directly proprtional to prior and likelihood

The null hypothesis is a fundamental concept in statistics that acts as a baseline assumption for hypothesis testing. It represents the claim that there is no difference or no effect between the groups being compared. If experimental results show a significant difference that is unlikely to be caused by random chance, the null hypothesis is rejected. If the results are ambiguous or easily explained by random variation, researchers fail to reject the null hypothesis. Summarizing, Null hypothesis treats everything same or equal.

Input -----> Statistical Test ------> Output (decision to reject or fail null hypothesis)

Statistical Test needs 3 things - data, null hypo, alternative hypo.

Alternative Hypothesis is the opposite of Null Hypothesis.

There can be multiple alternative hypotheses, especially when working with three or more groups of data. While the null hypothesis remains the same, that there is no difference between the groups, the choices for how to define the alternative hypothesis is based on what we are investigating.

For example, when comparing three drugs (C, D, and E):

All groups are different: One alternative hypothesis could be that all three drugs perform differently from one another, requiring to measure the distances from separate means for each drug.

Specific groups differ: Another alternative hypothesis might be that there is no difference between two drugs (e.g., C and D), but a third drug (E) is performing differently on its own, which would test by comparing a combined mean for C and D against a separate mean for E.

Because the choice of alternative hypothesis can influence the outcome of statistical test and the decision regarding the null hypothesis, it is crucial to clearly state which alternative  is being tested.

p value  is a number between 0 and 1 that helps researchers determine how confident they should be that the results of an experiment are significant, rather than just occurring due to random chance. The closer a p-value is to 0, the more confidence we have that the observed difference is real (statistically evient) and not random. common value is 0.05. if p value less than 0.05, reject null.

Confidence Interval - Rather than guessing a single exact number (like saying the average height is exactly 165 cm), a Confidence Interval gives us a safe range (like 160 cm to 170 cm). A 95% confidence level means that if we take 100 different samples and make an interval for each, we can expect about 95 of those 100 intervals to include the true population value.

Selecting the appropriate statistical test for hypothesis testing -

1. One-Sample Tests (Means & Proportions): Used to compare a sample mean or proportion to a known population value. T-tests are generally preferred over Z-tests due to the assumptions made by the latter.

2. Two-Sample Independent Tests: Designed for comparing two separate groups, such as a control group and a treatment group, to determine if differences in means or proportions are statistically significant.

3. Matched or Paired Sample Tests: Applied when samples are dependent, typically by measuring the same group twice—for example, before and after an intervention.

4. Regression Tests: Used to measure the correlation or association between two quantitative variables.

5. Chi-Squared Tests: Used to determine relationships between two qualitative (categorical) variables where quantitative graphing is not possible.

6. One-Way ANOVA: An extension of the two-sample independent test used when comparing means across three or more independent groups.