# One Sample T Test

## Software requirements

IBM SPSS 2.5

## Use case

A company studied the relationship between vitamin E deficiency in diet and vitamin a content in liver. They paired rats of the same genus with rats of the same sex, age and weight.

Eight pairs were randomly assigned to the normal feed group (group A) and vitamin E deficiency group (group B).

After a certain period of time, the content of vitamin A in liver was measured. Data is as shown in data-paired-samples.txt,

Question: Does Vitamin E deficiency has a significant effect on vitamin A? (α= 0.05)

## Results

H0 : μ0 ＝ μ1
H1 : μ0 ≠ μ1

![image](https://raw.githubusercontent.com/fuguixing/statistics/master/hypothesis-testing/paired-samples-t-test/paired-sample-t-test.png)

Figure 1 shows that the average value of group A is 3318.75, and the average value of group B is 2506.25
Figure 2 shows that The correlation coefficient of group A and group B is 0.584, and the test probability is 0.129
Figure 3 shows that The test p value of the mean value of the two samples is 0.004

0.004 < 0.05, we reject H0 and accept H1

So, we think that Vitamin E deficiency has a significant effect on vitamin A
