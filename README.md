# End-of-Phase1-Project

We got a dataset that approached student achievement in secondary education of two Portuguese schools. The data attributes include student grades, demographic, social and school related features and it was collected by using school reports and questionnaires. One of the datasets pertained to Portuguese language class and the other dataset pertained to Math class.

# Observations

I was focused on determining whether or not parents living together or apart had a direct correlation on students academic performance. I also focused on whether or not students drinking during the week and/or on the weekends had a direct correlation on students academic performance. After close analysis of our dataset and the newly aquired data from cleaning, we understand that there isn't much data to pull from for the Pstatus column. That particular column took data from students whether or not their parents lived together or apart. So there wouldn't be enough data between the two values of together and apart to form a conclusion of whether or not it had an effect on student performance.

So focusing on now on the weekend and weekday drinking, I realized that most of the students didn't drink during the week. However, more students were drinking on the weekend more than than during the week or drinking at all.

In order to proceed with our statistical analysis, we need to formulate our null and alternative hypothesis based on the topic we have been tackling. So far, we have been basing our analysis around whether or not alcoholic drinking during the weekday and weekend has an effect on student academic performance. We have also tackled the possibility of whether or not the students living together or not had an effect on the students academic perfomance.

Since there was only 41 students who's parents were seperated compared to the 354 who lived together in the math class, we can get rid of that topic since we do not have enough data to determine whether or not parents living together or not would affect students academic performance. There was also only 80 students who's parents were seperated compared to the 569 who lived together in the portuguese class.

So for now, our null hypothesis for the topics we were analyzing is that there is no impact between drinking during the week and on the weekends and student academic performance. The alternative hypothesis is that there is an influence with drinking and students academic performance.

According to my results, my Linear Regression Model for the math class gave me a Mean Squared Error of 5.159109091114173 and an R- Squared value of 0.79768240118271.

With my Ridge Regression Model, I got a train score of 0.8402653586165508 and a test score of 0.7976315083661282.

With my Lasso Regression Model, I got a train score of 0.46239462200687276 and a test score of 0.4103450043103516.

So all in all my Ridge Regression Model performed better on my dataset and gave me a better result. It peanlized the coefficients by bringing them closer to 0.