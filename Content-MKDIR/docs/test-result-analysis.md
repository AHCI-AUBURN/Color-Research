# Test Result and Analysis

###__Descriptive summary of data__  
####figure 1  
![image1](images/AnovaTable.PNG)

###__Box-plot of reverse contrasts and their data spread for time/duration__  
####figure 2  
![image1](images/data_analysis_1.jpg)

###__Histogram to show entire dataset distribution for time/duration__
####figure 3.
![image1](images/data_analysis_2.jpg)  

##__Stage 1__  
### Result Summary  
The data tells us that there is some difference in the spread for scanning times between Black text on white background (B/W)  and “White text on black background” (W/B). In figures 1 and 2 we can see that people did better on average with B/W but whether this is a statistically significant difference requires further testing. 
Our hypothesis “Is there a significant difference in scan-reading time between articles with B/W and W/B contrast?” requires a One-way ANOVA or single factor ANOVA test, however, according to "One-way ANOVA in SPSS Statistics - Step-by-step procedure including testing of assumptions” (2016)  there is an assumption that data needs to be approximately normally distributed. Looking at figure 3 we can see that the entire dataset is positively skewed which therefore requires us to conduct a test of normality (covered in the next section) to make sure that ANOVA can still handle this data set. 
Another two assumptions for ANOVA - the first being that there are no outliers in the data (In figure 2 there are a few outliers on both B/W and W/B)and the other ast assumption is the variances of both B/W and W/B being homogenous.
  

<hr>

###__Data normality testing__
####figure 4.
![image1](images/Normalization1.PNG)  

###__a. Lilliefors Significance Correction__  
####figure 5.  
![image1](images/data_analysis_3.jpg) 

####figure 6.  
![image1](images/data_analysis_4.jpg)  

##__Stage 2__  
### Summary of normality testing  
According to figure 4 results and using "Testing for Normality using SPSS Statistics when you have only one independent variable. (2016), the data set is not normally distributed. The sig value is quite a bit under 0.05 which tells us to reject the hypothesis that the data is normally distributed. This is further shown by the normal Q-Q plots for the reverse contrasts as the plots are quite a distance from the regression lines. This indicates the data is not normal. This means that we cannot conduct an ANOVA test without transforming the data to be normalized in which we will discuss in the next section.  


###__Data transformation__  
We decided that normalizing the entire time variable would fix both the skewness value in the data set as well as the kurtosis value (outliers). Using this 2-step process followed from “A Two Step Transformation to Normality in SPSS (2014), we used fractional ranking and a normalization function within SPSS software allowed us to get the best results which we will present below.  
 

<hr>

###__Descriptive statistics of transformed data__  
####figure 7.  
![image1](images/Descriptives.PNG)  

###__Box-plot of normalized reverse contrasts and their data spread for time/duration__
####figure 8.  
![image1](images/data_analysis_5.jpg)  

###__Data distribution__  
####figure 9.  
![image1](images/data_analysis_6.jpg)  

###__Data normality testing__
####figure 10.
![image1](images/TestsofNormality.PNG)  

####figure 11.  
![image1](images/data_analysis_7.jpg)  

###__Levenes test of Homogeneity__  
####figure 12.  
![image1](images/Homo.PNG)  

####figure 13.
![image1](images/data_analysis_8.jpg)  

##__Stage 3__  
###Normalizing the Dataset
Normalizing the data set had the desired effect. Looking at figure 7, the skewness and kurtosis values have been reduced considerably.  The outliers issue has been resolved by normalizing the entire variable without removing any of the outliers (shown in figures 8 and figure 9, the histogram shows the data set normally distributed.
To confirm this further we conducted a normality test (figure 10) on the normalized variable which shows both B/W and W/B Sig values are way over 0.05 which means we can accept the hypothesis that the data set is normally distributed. Figures 11 and 12 further shows that the data is normal because the plots are quite close to the regression line on both Q-Q plots.
Another requirement for ANOVA is variance homogeneity of which we undertook a Levene test with the data set (figure 13). The results show that the variances between both contrasts are indeed homogeneous with a Sig value way over .005. 
With all these issues addressed the data is now ready for One-way ANOVA testing in which we will compare the means for both B/W and W/B.  

<hr>

###__One-way ANOVA Test (Single-factor ANOVA__  
####figure 14.  
![image1](images/ANOVATest.PNG)  

###__Interval plot for B/W and W/B Means__  
####figure 15.
![image1](images/data_analysis_9.jpg)  

####figure 16.  
![image1](images/number_of_lines_average_story_performance_combo.PNG) 

##__Stage 4__  
###Discussion of one-way ANOVA results  
At first glance we can see the Sig value (p) for the One-way ANOVA test (figure 14) is below 0.05 which means we accept that the means have a statistically significant difference in scan-reading speeds between B/W and W/B articles. Further feedback from the students we were sampling found the B/W articles easier to search through except 1 who stated he developed software in IDE with dark backgrounds and light texts.
This, however, does not disprove previous findings in research we used to test this hypothesis. For instance our study did not take into account the location of the target-phrase within the articles.          A little bit of exploratory analysis at the data (figure 16) shows that scan-reading performances line up almost perfectly with the B/W articles. As a result of the random placement of target-phrase - the W/B articles had the target-phrase situated between 20 - 45. The one discrepancy is article 7 which on average took a lot longer for students to search through despite the target-phrase being on line 10. One reason for this could be that the target-phrase was on the end of line 10 meaning the rest of the phrase was on line 11. The entire phrase in article 7 was only able to be picked up by reading each line carefully left to right rather than properly scan-reading the document. This shows an error in our experiment design not taking into account target-phrase location factor having a considerable effect on scan-reading speed(not only vertically but horizontally). We did not take measures to isolate the target-phrase location variable. 
Another issue is that our sample population was extremely small (6 students) hence the sample may data may not reflect reality. 
Future experiment design around this area of research would need to take these details into account to give better quality results.  

##References used  
One-way ANOVA in SPSS Statistics - Step-by-step procedure including testing of assumptions.. (2016). Statistics.laerd.com. Retrieved 20 October 2016, from https://statistics.laerd.com/spss-tutorials/one-way-anova-using-spss-statistics.php

Testing for Normality using SPSS Statistics when you have only one independent variable.. (2016). Statistics.laerd.com. Retrieved 20 October 2016, from https://statistics.laerd.com/spss-tutorials/testing-for-normality-using-spss-statistics.php  

A Two Step Transformation to Normality in SPSS. (2014). Youtube.
https://www.youtube.com/watch?v=twwT6FgwlAo