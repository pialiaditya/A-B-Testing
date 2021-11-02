# A-B-Testing
Statistical analysis of A/B test run by an e-commerce website

An ecommerce website runs a A/B test to see if the new or treatment page leads to more conversion compared to the old page. 

The null hypothesis is p_old >= p_new

Alternate hypothesis is p_new>p_old

where p_new and p_old are the proportion of conversions for the new and old page respectively.

We perform hypothesis testing and calculate the p values using two techniques

i) Bootstrapping: we simulated the null distribution under the assumption p_new=p_old and calculated the p value = 0.907. 
ii) ztest. We use proportions_ztest from stats module to confirm the p value.

In conclusion we find that with the large p value we cannot reject the null hypothesis. 
