# School_District_Analysis
## Overview of Project
The project entailed analyzing school district data and highlight the trends in school performance. The data involved math and reading test results from ninth to twelfth grade from numerous schools statewide. 

### Purpose
The School Board is concerned with academic dishonestly among the ninth grade reading and math scores for Thomas High School. The purpose of this analysis is to remove the data, reading and math scores, from the ninth grade class for Thomas High School and determine if the scores influenced the overall results from the previous school district analysis.

## Results

### District Summary:
-  District summary before data was cleaned:

![District_Summary_before](https://user-images.githubusercontent.com/96746207/159102815-ba8b205a-3229-49ca-917c-6f35b1aaf851.png)

 - District summary after excluding ninth grade test results from Thomas High School

![District_summary_after](https://user-images.githubusercontent.com/96746207/159102844-983183c2-5a61-44a2-8ec1-5c82453f99e7.png)


Comparing the above screenshot, minimal change in the district summary once the ninth grade test scores from Thomas High School was eliminated. The district summary isn’t affected by removing the above data.  

### School Summary:
 - School summary before data was extracted:
 
![School_summary_before](https://user-images.githubusercontent.com/96746207/159102854-cd76d4e3-b750-4fb3-bfea-9634ab80e519.png)
	
 - School summary with data extracted:

![School_summary_after  png](https://user-images.githubusercontent.com/96746207/159102869-c43459ce-213c-4e00-b4ac-f8de64fdafd3.png)

Comparing the two school summary screenshots, Thomas High School had a significant drop in ranking once the ninth grade reading and math scores were removed. They went from an 91% overall passing to a 65% overall passing rate. The school summary was negatively affected when removing the above data. 	

### Replacing the ninth grade math and reading scores affect Thomas High School’s performance relative to the other schools by the following: 
 - Thomas High School changed from second place to eighth place ranking when replacing the above data.


### Replacing the ninth grade scores affect the following:
 - Math and reading scores by grade level
   - Both scores were set to NaN for all ninth graders for Thomas High School, scores were replaced with zeros. Example below of removing scores for math and the output is NaN:

![math](https://user-images.githubusercontent.com/96746207/159135269-04a0a099-30c2-4a10-aecf-70551ccbbb33.png)
 
   - Student count before NaN:1635
![count before](https://user-images.githubusercontent.com/96746207/159135886-96d453c5-2c0f-48e6-bcb5-7cd7aa27beac.png)

  - Student count with NaN: 1174
 
 ![withNaN](https://user-images.githubusercontent.com/96746207/159136084-9f266a9d-cd0c-46b3-bdae-84b63794ae87.png)


- Scores by School Spending:
   - Removing the ninth grade students from Thomas High school reduces the school spending


 - Scores by School Size:
   - Removing the ninth grade student reduces the scores for size bucket.

 - Scores by School Type:
   - Thomas High School is a charter school. However, no significant changes when comparing the school type when comparing the two data frames.

## Summary
Four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
 1. Thomas High School dropped in ranking from second to eight.
 2. School size was also decreased but overall passing percentage didn’t change
 3. Scores by school spending had no significant change.
 4. Scores by school type had no change.

Overall, no significate changes occurred in school size, type, spending, and district summary once we replaced the scores of the Thomas High School ninth grade reading and math. However, school summary witnessed the largest disparity. 



