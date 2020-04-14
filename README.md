This package will calculate conditional power for stopping a trial for futility or stop for efficacy. 
It is possible to calculate the conditional power of the study to reject the null hypothesis given the 
current results obtained from gsDesign (Group sequential designs). gsDesign gives the opportunity to 
stop the study early for efficacy or stop for futility. Stop for efficacy means faster access to the 
new treatment during an interim analysis. On the other hand, stop for futility means unknown true effect 
is far away from the anticipated effect under the alternative hypothesis. As a result it saves time and 
financial resources and perhaps those resources can be reallocated to more productive undertakings. 
There is also ethical motivations as well. It might be inappropriate to ask patients to contribute 
their continued participation in trials in which the high-level outcome seems already clear. 

The decision of stopping a trial with early rejection of either the null or the alternative hypothesis, 
if a given test statistic crosses a given stopping boundary. This strategy was executed in design phase 
and interim monitoring phase. An user has to first calculate the sample size for any types of endpoint: 
Continuous, Binary and Time-to-Event based on R-package gsDesign. Then using this results one can 
calculate the Conditional power, which is one of the tools, when computed over a range of alternatives, 
can be of guidance in
deciding whether to continue the study given those available information. 

It is important to note that conditional power at the beginning of the study before any data are 
collected is equal to the unconditional power. Unconditional power is the probability of achieving 
a significant result at a pre-specified alpha under a pre-specified alternative treatment effect as
calculated at the beginning of a trial.
