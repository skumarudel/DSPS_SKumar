# READING: 
Read the paper you re reproducing in KS_earthquakes.ipynb: [Corral 2018](https://arxiv.org/pdf/0910.0055.pdf).
I am not trying to turn you into an earthquake specialist, so you do not need to absorbe all of it in detail. Focus on understanding the goal and how the KS test was used to achieve that goal. 

# WATCHING: 
Geoff West [TED talk](https://www.ted.com/talks/geoffrey_west_the_surprising_math_of_cities_and_corporations?utm_campaign=tedspread&utm_medium=referral&utm_source=tedcomshare) about scaling laws in phsyics from biology to urban science

Work in groups of 3 to 5 people. 
Remember to include a README.md, in markdown format, that states how your team worked: who you worked with and what you contributed specifically.

#  KS test 
- I (Sajan Kumar) have created this notebook [Kolmogorov_smirnov_earthquake.ipynb](Kolmogorov_smirnov_earthquake.ipynb) to reproduce the use of the KS test in [Corral 2018](https://arxiv.org/pdf/0910.0055.pdf).
- Understand the concept of Null Hypothesis. For instance, how to define the value of probabilitiy threshold (2 sigma, 3 sigma or higher) to reject the null hypothesis before starting the data analysis. This is important not to bias the outcome after looking at the results. In physics, this threshold is very strict at a level of 5 sigma to claim any discovery. However, in social sciences this number can be 3 sigma.
- Notebook explain the concept of KS test and where we use it. For example, to test if the two datasets belongs to same distribution. Here the Null hypothesis is defined as two datasets belongs to same distribution. We then calculated the KS-statistics and the probabiltiy associated with it. We then compare this probability with the threshold probability (define before we start the analysis) to accept or reject the null hypothesis. 
- Interpretations of the results are consistent with the Corral 2018 paper although the numbers are not exactly same for the KS test probability. This is due to slighlty different datasets.
 
