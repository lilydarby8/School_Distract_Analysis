# School District Analysis

## Overview
This school district analysis takes the reading and math scores from 15 different schools spanning over 4 different grade levels and organizes the data into categories for the score averages of both reading and math as well as the percentages of passing and the percentage of overall passing.

### Purpose
The purpose of this analysis is to provide the school board with the accurate scores of the students from 9th to 12th grade as well as the trends that coincide with the students scores. Included with the students’ scores are gender, what grade they are in, what high school they enroll in, and the averages of their scores, the percentages of their scores, the budget for each school, and the type of each school. 


## Results


- How is the district summary affected?

The two district summaries have small differences. The only categories affected, after the 9th grade scores from Thomas High School were replaced with NaNs, were the average scores, percent passing, and overall passing. The numbers only had a .03 or .02 difference, with the average reading score staying the same. 

*The first link will be from the original analysis and second link will be from the updated analysis*
![This is an image](https://github.com/lilydarby8/School_District_Analysis/issues/1#issuecomment-1179657024)
![This is an image](https://github.com/lilydarby8/School_District_Analysis/issues/1#issuecomment-1179657082)


 
- How is the school summary affected?

The school summary was noticeably affected in the percentage columns of the data frame. Up until the “% Passing Math” the numbers varied slightly from the original analysis. The following numbers illustrate the changes from each analysis:
“% Passing Math” went from 93% to 67%.
“Passing Reading” went from 97% to 70%.
“Overall Passing went from 91% to 65%.
The significant changes may be due to the fact how each value was calculated. When the average was taken it only divided by how many actual values were recorded whereas with the percentage it was divided by how many students were recorded regardless of if the student had a grade inputted or not. However, when the 10th through 12th grades were added to the school summary the percentages became very close in number to the original analysis. 
![This is an image](https://github.com/lilydarby8/School_District_Analysis/issues/1#issuecomment-1179658141)
![This is an image](https://github.com/lilydarby8/School_District_Analysis/issues/1#issuecomment-1179658526)
![This is an image](https://github.com/lilydarby8/School_District_Analysis/issues/1#issuecomment-1179658641)


- How does replacing the 9th graders math and reading scores affect Thomas High School’s performance relative to other schools?

Thomas High School did very well with their score and their percent of passing. They were above average in each category
In math scores the average was 80.4 and Thomas High School had an average of 83.4.
In reading the average was 82.6 and Thomas High School had an average of 83.8.
In Percent Passing Math the average percentage was 81% and Thomas High School had 93%.
In Percent Passing Reading the average percentage was 89% and Thomas High School had 97 %.
In the Percent Overall Passing the average percentage was 73% and Thomas High School had 90%.


- How does replacing the ninth-grade scores affect math and reading scores by grade?

In both the math and reading scores by grade, the 9th grade column for Thomas High School has the “NaN” value to represent 9th grade. ![This is an image](https://github.com/lilydarby8/School_District_Analysis/issues/1#issuecomment-1179658814)
![This is an image](https://github.com/lilydarby8/School_District_Analysis/issues/1#issuecomment-1179658957)
![This is an image](https://github.com/lilydarby8/School_District_Analysis/issues/1#issuecomment-1179659058)
![This is an image](https://github.com/lilydarby8/School_District_Analysis/issues/1#issuecomment-1179659136)

- How does replacing the ninth-grade scores affect scores by school spending? 

The $631-644 spending range is the only spending range that varies. It is a very slight difference with the whole number not being affected. 


- How does replacing the ninth-grade scores affect scores by school type?

The replaced ninth-grade scores do not affect the school type summary.

## Summary

In conclusion the updated School District Analysis made slight changes in the data outcome but provided the School Board with a more accurate analysis of the schools and their students’ grades. A few differences between the two analyses’ are below:

The district summary numbers either stayed the same or had a .02 or .03 difference to the averages and percent passing columns.

The school summary that was calculated before adding the 10th through 12th grades had significant changes but did not affect Thomas High School as a whole. Later in the analysis when the other grades were added the data became very similar to its predecessor with only slight changes to the numbers after the decimal point in the averages and percent passing columns.

The math and reading scores by grade were noticeably changed in the updated analysis. In the original analysis Thomas High School had an 83.6 as their average math grade and an 83.7 for their average reading grade for the 9th grade. However, in the updated analysis both values are replaced with “NaN”.

The school spending summary had changes in their numbers because Thomas High School had $631-645 as their spending range per student. In that spending range these are the contrasts in the two data frames.
In the original and the updated analysis, the “Average Math Score” and the “Average Reading Score” stayed the same. However, the “% Passing Math” in the original analysis was 67% but in the updated analysis it is 73. 
In the original analysis the “% Passing Reading” was 77% but in the updated analysis it is 84%.
In the original analysis the “% Overall Passing” was 56% but in the updated analysis it is 63%.

