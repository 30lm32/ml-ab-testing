
### A/B Testing to Distinguish Impact of Version of Landing Page on User

![](https://receiptful-blog-staging.s3.amazonaws.com/2015/Apr/a_b_testing-1430250346717.jpg)

|__Problem__|__Data__|__Methods__|__Libs__|__Link__|
|-|-|-|-|-|
|`Conversion`|Retail|`A\B Testing`, `Z test`|`pandas`, `statsmodel`|https://github.com/erdiolmezogullari/ml-ab-testing|

In this project, A/B testing was performed on Udacity's Course dataset. It consists of 5 columns, `<user_id, timestamp, group, landing_page, converted>`. In A/B testing,  we used 3 columns of out of them, `group, landing_page, and converted`.

 We once simulated some experiments N times with respect to the conversion rates (`control, treatment`) already obtained over dataset. After got the further idea about dataset with this simulation, we supposed a null hypothesis and an alternative thesis. To claim our trueness of alternative hypothesis, we calculated z critical score by using `Z test` method with respect to alpha (0.05), and then we checked out beta, and power with respect to the effect size of the experiment.

Please, note that you may check out [`ab_test.md`](/ab_test.md) to get the further information about hypothesis test and A/B testing with some important photos.
