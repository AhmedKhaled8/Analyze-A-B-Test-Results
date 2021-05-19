# Analyze-A-B-Test-Results

**This is the second project in the 'Advanced Data Analysis' nanodegree provided by FWD-Egypt.**

We have a data set that contains results of an A/B test run by an e-commerce website. The company has developed a new web page in order to try and increase the number of users who "convert," meaning the number of users who decide to pay for the company's product. Our goal is to help the company understand if they should implement this new page, keep the old page, or perhaps run the experiment longer to make their decision.


## Conclusions:

1. Like we concluded in the A/B testing part, the p-values of the difference between using a new and old page wasn't statistically significant different. In the A/B testing, we saw that we couldn't reject the null hypothesis which was that new page was converted less or equall to the old page. In the regression part, we saw that the predictor of either the page was the old or new page wasn't significant colorated to the output of conversion.

2. Adding country alone, with the ab_page or doing an interaction between them didn't provide statistically siginficance in our prediction.

3. We don't have sufficient evidence to reject the null hypothesis in favor to the alternative hypothesis. We tell the company that we shouldn't implement the new page as we can't say it will do better than the old page IN THE PRESENCE OF THIS DATASET.
