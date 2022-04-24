# School_District_Analysis

## Overview of the School District Analysis 
The purpose of this analysis was to understand how different school metrics (ie spending, size, and type) could be correlated with standardized testing scores. After discovering there was possible academic dishonesty at Thomas High School (THS) in the 9th grade, we wanted to ensure we re-did the analysis and remove possible “dishonest” scores before evaluating the scores. To do so we replaced all 9th grade standardized test scores for Thomas High School with NaN values, so they would not imapct the metrics we were analyzing

## Results
* How is the district summary affected?
  * District summary showed just slightly lower pass rates for math, reading and overall.

#### Before replacing 9th Grade THS Scores: ![image description or alt text](https://raw.githubusercontent.com/charlotterotner/School_District_Analysis/main/Resources/module_district.png)

#### After replacing 9th Grade THS Scores: ![image description or alt text](https://raw.githubusercontent.com/charlotterotner/School_District_Analysis/main/Resources/challenge_district.png)

* How is the school summary affected?
  * When we zoom in on Thomas High School in the school summary the overall and math and reading scores were much higher prior to replacing the 9th grade scores with NA's.

#### Before replacing 9th Grade THS Scores: ![image description or alt text](https://raw.githubusercontent.com/charlotterotner/School_District_Analysis/main/Resources/school%20summary_module.png)

#### After replacing 9th Grade THS Scores: ![image description or alt text](https://raw.githubusercontent.com/charlotterotner/School_District_Analysis/main/Resources/school%20summary_challenge.png)

* How does replacing the ninth-grade scores affect the following:
  * Math and reading scores by grade: Math and reading scores by grade outputs the same except for 'nan' is displayed for the 9th grade scores. Below are images of the reading scores after we replaced the 9th grade scores:

![image description or alt text](https://raw.githubusercontent.com/charlotterotner/School_District_Analysis/main/Resources/Scores%20by%20Grade.png)

  * **Scores by school spending**: Scores by school spending was not impacted by replacing the 9th grade THS scores.
  
  ![image description or alt text](https://raw.githubusercontent.com/charlotterotner/School_District_Analysis/main/Resources/spending.png)
  
  * **Scores by school size**: Scores by school size was also not impacted by replacing the 9th grade THS scores.
 
 ![image description or alt text](https://raw.githubusercontent.com/charlotterotner/School_District_Analysis/main/Resources/size.png)
  
  * **Scores by school type**: Scores by school type was also not impacted by replacing the 9th grade THS scores.
 
![image description or alt text](https://raw.githubusercontent.com/charlotterotner/School_District_Analysis/main/Resources/Type.png)
  

## Summary
As pictured in our results above, we saw that replacing the 9th grade THS scores with NaNs impacted the metrics for Thomas High School as an individual school the most, but not the overall analysis for all schools in the data set. When we removed the THS 9th grade scores we saw the following metrics change for Thomas High School:

  * Average Math Score dropped from 83.4 to 83.3
  * Average Reading score dropped from 83.8 to 83.8
  * Percent Passing Math dropped from 93.2% to 66.9%
  * Percent Passing Reading dropped from 97.3% to 69.6%
  * Percent Overall Passing dropped from 90.9% to 65.0%

The process to replace the 9th grade scores with NaN's was essential for understanding Thomas High School's standardized test performance as an individual school, and we can see that the passing rates are much lower after replacing the scores. That being said, replacing the 9th grade THS scores did not impact the overall analyis of all schools combined with the district scores being changed by less then 1 "point" or percentage in passing scores.
