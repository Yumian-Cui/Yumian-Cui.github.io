---
title: 'Stats notes on hypothesis testing and p-value'
date: 2020-11-28
permalink: /posts/2020/11/blog-post-1/
tags:
  - stats
  - hypothesis testing
  - p-value
---

Take some time to refresh my understanding towards `p-value`  and keep a note here

-----

I feel this topic is rather important and worthy to dive into as 3 out of my 4 courses this semester have covered this concept. Yet having learned p-value and hypothesis testing on my AP course early since high school and my college introductory stats course, it always remains a bit foggy. Thus, in case I can't think straight at some point in the future, it would be good to review for consolidataion of understanding. 

**What does it actually mean to reject the null?**

Rejecting null doesn't mean it's true, it just means we fail to prove it's false. H0 and H1 are not the opposites. It's not like one way or the other. Assume null is true, there has happend a low probability event. It seems too rare to happen but if it does happen, then it's reasonable to suspect the validity of the null. 

**Hypothesis testing**

According to Wooldrige's textbook: there're two approaches. 
* Classical: compare critical value with test statistic, if test statistic > critical value, then reject, because we get a sufficiently large value compared to the null. 

ps: as alpha significance level decreases, the critical value increases, which means it becomes harder to reject the null and one needs larger test statistic for rejection. For example, if I can reject the null at 5 % significance level, I can surely reject it at 10%. 

* p-value: calculate p-value and compare it to sigficance level, if p-value < significance level, reject the null, vice versa. 

ps: more about p-value: "Given the observed value of the t statistic, p value is the smallest significance level (alpha)  at which the null hypothesis would be rejected."(Cited from Wooldrige) To put it in my own understanding, if p-value is 0.03, it means we would observe test statistic as extreme 3% of time when null is true. Smaller p means stronger evidence against H0. To compare it with alpha the signficance level is to make sure if we were to reject the null 3% of time, it should be within the tolerance of error(the significance level), say if alpha is 0.05, we're willing to accept mistakenly reject the null 5% of time when it is actually true. Why say p-value is the smallest significance level? if we calculate p to be 0.03 and we can reject the null at 3% significance level, we can certainly reject this at 5% if set by the question. 








