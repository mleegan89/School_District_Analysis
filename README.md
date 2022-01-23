# School_District_Analysis

## Overview of Analysis
The purpose of this analysis we were tasked to complete by Maria was to determine the effect that a potential cheating scandal in the ninth grade at Thomas High School had on the results. In order to accurately conduct this analysis we wanted to remove the data that was from all ninth grade students at Thomas High School and then report on that data. 

## Results

- How is the district summary affected?
<img width="703" alt="image" src="https://user-images.githubusercontent.com/96085210/150695826-b3889d40-05fd-4850-a349-a61174b906b4.png">
Because of the small amount of data that the 9th graders from this school represented out of almost 40,000 students there was little impact to the district summary numbers.

- How is the school summary affected?
The overall student summary is not affected by the removal of these ninth grades scores. All of the other schools' data and performances remain unchanged. 

- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
![image](https://user-images.githubusercontent.com/96085210/150696211-fcc734ab-ccfc-4d95-a703-ac190a4bc0fc.png)
When we look at just Thomas High School and we include the 9th grade that cheated we can see that the performance greatly decreases. This is because we are including all ninth graders and assigning them a score of 0 which skews the data. 

![image](https://user-images.githubusercontent.com/96085210/150696249-18a38fb4-40cf-4052-bc44-905e437fa072.png)
When we remove all of the ninth graders data the results go on to show Thomas High School as being among of the top 5 schools. 

How does replacing the ninth-grade scores affect the following:
 - Math and reading scores:
   The overall math and reading scores for Thomas High school increased slightly from the inital results (shown above) when we removed the ninth graders data.
   ![image](https://user-images.githubusercontent.com/96085210/150696422-f86b7eb7-9140-438b-ab52-0004cc6cd33f.png)

 - Scores by school size:
  The scores by school size remained almost unchanged.
  ![image](https://user-images.githubusercontent.com/96085210/150697400-3ff62e98-cf9b-4b9a-bf7d-f05683a51c60.png)


 - Scores by school spending:
   The scores by school spending remained unchanged.
   ![image](https://user-images.githubusercontent.com/96085210/150697387-b80461be-07ca-4278-9145-59a1ea4ef72b.png)

  - Scores by school type:
    The scores by school type remained unchanged. 
  ![image](https://user-images.githubusercontent.com/96085210/150697350-90cc2017-f625-41b5-8fbb-291b5616481f.png)

## Summary
 
 After conducting this analysis we determined that when we remove the ninth graders data from Thomas High School the overall results remain almost identical. The only thing affected was the "% Percent Math", "% Passing Reading", and "% Overall Passing" for Thomas High School's data. When we replaced all of the ninth graders at Thomas High School results with "NaN" we saw that Thomas High Schools' performance greatly suffered. 
