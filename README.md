# School_District_Analysis.

## Overview of Project
Analyzing the school district grades in order to find the top schools and the bottom school and understand what affect the school grades.

### Purpose
Using the Student complete dataset to understand the different schools' achievements. 

## Challenges and Solutions
The school board thinks the Student's complete file shows evidence of academic dishonesty in order to solve this we adjusted the math and reading scours for Thomas High School, 9th-grade students to NaN, so this data will not affect the total scores.   

#### The reading and math scores for the ninth graders in Thomas High school are replaced with NaNs
![Reading_and_math_scores_9th_graders_THS_are_NaNs.png](Resources/Reading_and_math_scores_9th_graders_THS_are_NaNs.png)

## Results

 - The district summary DataFrame 
![district_summary_df.png](Resources/district_summary_df.png)

 By replacing Thomas High School, 9th-grade score we can see the district summary scores have a minor decrease.
 
 The school summary affected by this change only on the Thomas High School row. It is affecting the other schools when we look at the sum/ average/ mean of all the schools..

- The top 5 performing schools, based on the overall passing rate
![5_top_schools.png](Resources/5_top_schools.png)

 We can see that Thomas High School is still in the top 5 high schools, the 9th grade has a small effect on the school total score.

- The average math score (left) and reading score (right) for each grade level from each school.

 Replacing the ninth-grade scores affects the Math and Reading overall score for 9th grade.

![math_scores_by_grade.png](Resources/math_scores_by_grade.png)
![reading_scores_by_grade.png](Resources/reading_scores_by_grade.png)

- The scores by school spending per student 

![Scores_by_School_Spending.png](Resources/Scores_by_School_Spending.png)

 The spending per student didn't change but the scores has a small decrease.

- The scores by school size 
![school_size.png](Resources/school_size.png)

 The school size didn't change but the scoures show a small decrease. 

- The scores by school type
![Scores_by_School_Type.png](Resources/Scores_by_School_Type.png)

 The school size didn't change but the scores show a small decrease.

## Summary: 
Changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs
1. The average Math and Reading score
2. Percent of Math passing decreases by last than a point
3. Percent of Reading passing decreases by last than a point
4. Percent of overall passing decreases by last than a point

Because the ninth grade at Thomas High School is only 0.01% of the total students the changes we see are minor.
