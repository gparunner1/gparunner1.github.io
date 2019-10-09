## Portfolio

---

### Projects

[Dimension Reduction](/pdf/Gene_Expression.pdf)

We used two different methods to analyze gene expression data.  Gene expression data can be tricky to work with due to the large number of variables.  We first used elastic net to reduce the dimensionality of the data.  This method worked fairly well.  As a secondary method, we used principal components regression.  Using these two methods, we found a certain subset of genes that were associated with the occurence of cancer.

---
[Regression with Spatial Correlation and Heteroskedasticity](/pdf/Real_Estate.pdf)

Through use of a multiple linear regression model that accounts for heteroskedasticity and spatial correlation, we were able to successfully analyze our data.  First, we determined that by using the characteristics included in our model roughly 93% of the variation can be explained. Next, we determined that above-ground square footage, the year a home was built, the presence of AC, and the number of cars the garage can hold all have positive effects on sale price. That is, holding all else constant, a home with AC is probably going to more expensive than one without and a newer home will be more expensive than an older. Next we determined that sale price variability does increase as living area increases. Finally, we used our model to make appropriate predictions for sale price at locations for which we did not have it.

---
[Time Series #1](/pdf/PM.pdf)

In our analysis, we were able to use a regression model with interaction terms and an AR(1) correlation
structure to answer the research questions posed. We discovered that Stationary alone
does not explain log(Aerosol) well. Other information is needed. By including interaction terms between ID
and Activity, as well as ID and Stationary, we were able to quantify the differences in log(Aerosol) between
houses. We discovered that, on average, only one of the activities, playing on the furniture, had a statistically
significant effect on log(Aerosol). By analyzing some of the interaction effects, however, we were also able
to learn that playing on the floor and on furniture increases the amount of PM exposure for a great number
of children. Overall, we learned that PM exposure is highly individualized. It is difficult to make blanket
statements when each house is so different. However, by accounting for the differences between houses, our
model works fairly effectively at explaining different levels of PM exposure.

---

[Time Series #2](/pdf/Solar_Case_Study.pdf)

This analysis adequately addressed the research goals of this study. We were able to predict power output for this individual’s solar panels for 2018 and we were able to explore how the panels degrade over time. We found that there was a slight degradation from year to year by analyzing our coefficients and we computed the 2018 power output by using Gaussian Process Regression with an autoregressive 1 correlation structure. 
One of the shortcomings in our analysis was extrapolation for our predictions. The data we had for 2015-2017 wasn’t able to show the random increase in sunlight for 2018, which led to our predictions being lower than the actual values. Another issue with the analysis is the use of only the dates to predict kWh when other variables could be useful in prediction.
Going forward, it would be interesting to examine the effects of other variables like weather, temperature,
etc on kWh. It would also be interesting to look at multiple individuals’ solar panel data so we could compare
trends between different people.

---

[Stochastic Regression Imputation](/pdf/Employee_Study.pdf)

Through stochastic regression imputation, we were able to complete the goals of this analysis by filling in missing data, fitting appropriate models, and performing inference. We discovered that well-being has a positive impact on job performance, while job satisfaction does not appear to have a significant effect. Older professors do appear to care slightly less about their jobs than younger professors. IQ has a positive relationship with job performance: as IQ increases, job performance generally increases as well. Finally, well-being has a positive effect on tenure, while job satisfaction appears to have no significant impact on tenure.
One potential shortcoming of this analysis is that, because we used stochastic regression imputation, our standard errors could be too small. This would cause the confidence intervals for our estimates to be too small. Further analysis could try different imputation methods to fill in missing data. We could then compare standard errors. Also, since all our data came from one university, we cannot infer our results to other universities or other workplaces. Future research could involve gathering data from a greater variety of workplaces.

---

[Multiple Linear Regression](/pdf/1__Credit_Card_Report.pdf)

Through use of a justifiable multiple linear regression model, we were able to answer the questions posed at
the beginning of the analysis. Using the known variables Income, Limit, Cards, Age, and whether or not
someone is a student, credit card companies can accurately predict balances within a certain interval. This
predictive capability will allow credit card companies to better manage their risk and gain more profits.
We also discovered that as people age, their financial responsibility generally increases as well (lower
balances). This makes intuitive sense and could be a useful piece of information for credit card companies.
We also determined that the expected difference in balance for someone whose income increases by
$10,000 is approximately $221. The policy of the credit card company to increase credit limits by 10% of
an income increase seems reasonable, but could be improved by adding additional safeguards such as taking
into account total credit extended across all accounts.

---

[Weighted Multiple Linear Regression](/pdf/Pedagogy.pdf)

Through the use of a heteroskedastic multiple linear regression model, we were able to answer the questions
posed at the beginning of this analysis. Average scores for midterm exams and homework are associated
with final exam scores for this specific course. The association between the third midterm exam score and
the final exam score is particularly strong. Quiz scores and the semester to which a section pertains do not
have a statistically significant effect on the final score.
In deciding where to allocate resources for struggling students, administrators should focus on students
who have lower exam scores (and to a lesser extent, those with lower homework scores), and not necessarily
those with low quiz scores. A potential change to be considered for the course would be to eliminate quizzes
and add a fourth midterm exam, to better identify and aid struggling students.

---





---
<p style="font-size:11px">Page template forked from <a href="https://github.com/evanca/quick-portfolio">evanca</a></p>
<!-- Remove above link if you don't want to attibute -->
