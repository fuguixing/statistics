# Independent Sample T Test

## Software requirements

IBM SPSS 2.5

## Use case

The ash content of coal in coal mines a and B obeys the normal distribution. Several samples are taken from each of the two mines to analyze the ash content. The data is as shown in data-independent-samples.txt,

Question: is there any significant difference between the average ash content of the two coal mines? (α= 0.05)

## Results

H0 : μ0 ＝ μ1
H1 : μ0 ≠ μ1

![image](https://github.com/fuguixing/statistics/master/hypothesis-testing/independent-samples-t-test/independent-sample-t-test.png)

Sig. 0.396 indicates that the result of Equal Variances Assumed is valid
The results of t-test should be based on Equal Variances Assumed

Sig(2-tail) = 0.618

0.618 > 0.05, we accept H0 and reject H1

So, there is no significant difference between the average ash content of the two coal mines
