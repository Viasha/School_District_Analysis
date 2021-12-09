# School_District_Analysis
## Overview of School District Analysis
During this challenge I have aimed to use my Jupyter Notebook skills to reveal any dishonesty amongst the grades of Thomas High School students. The school board was notified to investigate the acedemic dishonesty. In order to analysis the students' grades, I was instructed to replace the math and reading scores of Thomas High School students to NaNs. Once thoses data points are removed I was instructed to re-analyze the data to see how the refracted grades would affect the overall analysis.

## Results
### How is the District Summary Affected?
When I composed a district summary while including the scores of all Thomas High School students, the average math and reading scores were 79.0 and 81.9 respectfully. When I disregarded the math and reading scores of the 9th graders at Thomas High School, the average math and reading scores were 78.9 and 81.9 respectfully. The overall passing percentage of both math and reading before the withdrawal of the 9th graders scores was 65%. After re-analyzing the scores the new overall passing percentage was 64.9%. The statical analyzes does not show a signficant change with or without the 9th grader's scores. 
![Disctrict Summary With 9th Graders of THS](Documents/DataAnalytics/Resources/District_Summary_with_THS.png)
![District Summary w/o 9th Graders of THS](Documents/DataAnlytics/Resources/District_Summary_withou_THS.png)

### How is the School Summary Affected?
The school summary dataset only took affect to Thomas High School. The overall passing percentage dropped from 90.9% to 65.1%. This is explainable because when calculating the averages the student count did not change. Although we no longer included the 9th graders scores, they were still included in the total student count. That had a major affect on the overall percentage of passing students at Thomas High School
![School Summary with 9th Graders of THS](Documents/DataAnalytics/Resources/School_District_Summary_B4.png)
![School Summary without 0th Graders of THS](Documents/DataAnalytics/Resources/School_District_Summary_after.png)

### How does 9th Graders' Scores Affect Thomas High School's Performance Compared to Others?
Unfortunately, the 9th graders's scores had a hard impact on Thomas High School's perfomance in a negative way. Before the 9th grade scores were removed, Thomas High School was amongst the top 5 schools. It ranked number 2 actually. After re-analyzing the data, Thomas High School ranked second to last in overall math and reading perfomance. Eventhough our dataset shows these rankings, it is unclear of Thomas High School's actual performance rankings because these calculations were made with out adjusting the total number of students. 
![Thomas High School's Performance with 9th Graders](Documents/DataAnalytics/Resources/Top_5_Schools.png)
![Thomse High School's Performance with out 9th Graders](Documents/DataAnalytics/Resources/Bottom_5_Schools.png)

### How Does Replacing the 9th Grade Scores Affect:
#### Math & Reading Scores by Grade
When replacing the 9th grade scores only Thomas High School's 9th graders were affected. All the other schools remained consistent while, 9th graders of Thomas High School's data changed to NaN as I entered it. This leaves a whole in the data for the re-analyzed dataset.
![Math Scores by Grade with 9th Graders](Documents/DataAnalytics/Resources/Math_Scores_With_9th.png)
![Math Scores by Grade without 9th Graders](Documents/DataAnalytics/Resources/Math_Scores_Without_9th.png)
![Reading Scores by Grade with 9th Graders](Documents/DataAnalytics/Resources/Reading_Scores_with_9th.png)
![Reading Scores by Grade without 9th Graders](Documents/DataAnalytics/Resources/Reading_Scores_without_9th.png)

#### Scores by School Spending
In order to effeciently analyze the spending data, I created bins to better oraganize the data. Thomas High School's budget per student is $638. Therefore I was able to focus on the bin within the range of $630-644. This is the only bin that took affect when withdrawing the 9th grade scores. Before removing the 9th grade scores the overall passing percentage was 62.8%. After removing the 9th grade scores the overall passing percentage was 62.7%. There was little no change in the scores by spending budget. This was unexpected to me because I beleive the overall passing percentage would go decrease since the average was not accurate with out adjusting the total number of students.
![Scores by School Spending with 9th Graders](Documents/DataAnalytics/Resources/spending_range_b4.png)
![Scores by School Spending without 9th Graders](Documents/DataAnalytics/Resources/spending_range_after.png)

#### Scores by School Size
I also organized the data into bins in order to effeciently observe the statical analyzes based on school size. Thomas High School has a total number of 1635 students. Therefore Thomas High School is included in the bin labeled 1000-2000. Both the average math and reading scores stayed pretty consistent. There was a minimal change in the overall passing percentage from 90.6% with the 9th grade scores to 90.5 with out them. 
![Scores by School Size with 9th Graders](Documents/DataAnalytics/Resources/school_size_b4.png)
![Scores by School Size without 9th Graders](Documents/DataAnalytics/Resources/school_size_after.png)

#### Scores by School Type
After analyzing the final category of school type, this category also was not affected much. Thomas High School is a charter school. The overall passing percentage with the 9th graders included is 90.4% and after removing the 9th grade scores the overall passing percentage is 90.3%. Similarly to the school size, and speding budget, the school type was not majorly affected by the 9th grader's scores.
![Scores by School Type with 9th Graders](Documents/DataAnalytics/Resources/type_b4.png)
![Scores by School Type without 9th Graders](Documents/DataAnalytics/Resources/type_after.png)

## Summary
After replacing the 9th grade students of Thomas High School with null values it affected the math scores by by 0.1% and did not affect the reading scores. The overall percentage was also affected by 0.1%. After adjusting the school summary data the overall passing percentage took a drastict drop from 90.9% to 65.1%. The performance ranking of Thomas High School took a major negative turn also. Before removing the 9th grade scores, Thomas High School was ranked 2nd out of the 15 schools. Once removed, Thomas High School was ranked 13 out of 15. All other categories were adjusted by 0.1% or less.  







