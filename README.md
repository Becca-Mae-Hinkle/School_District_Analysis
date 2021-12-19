# School_District_Analysis

## Overview

The ninth graders, at Thomas High School have had their math and reading scores tampered with. While we don't know the full extent of this dishonesty, the administrators want to uphold the integrity and standards of the state mandated testing. We have been brought in to do a full analysis of the situation and report our findings. We have decided to replace all ninth-grade math and reading scores from Thomas High School. All other data associated with ninth-grade students at Thomas High School will stay intact.

## Objectives

* Filter DataFrames.
* Replace the incorrect values with NaN.
* Explain how your analysis changes with clean data.

## Results

How is the district summary affected?

![District Summary](https://user-images.githubusercontent.com/94575416/146692215-3a1f014d-baf1-4ea9-8dc9-23c98eac3a3e.png)

### * How is the school summary affected?
      - Thomas High School Original Data - 91% Overall passing - Placing second in the district
                           Clean Data - 65% Overall passing - Placing eighth in the district
                                                      
                           
### * How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
      Thomas High School's performance took a big hit going from 2nd in the district to 8th.


### How does replacing the ninth-grade scores affect the following?
   - Math and reading scores from Thomas High School
   
   Original Data - Average Math Score - 83.6

![9th Grade Math Scores (original data)](https://user-images.githubusercontent.com/94575416/146691291-a2ec8dc2-d367-4501-a9ad-3a11b52e89c8.png)

   Clean Data - Average Math Score - 78.9

![Avg Math Score (Clean Data)](https://user-images.githubusercontent.com/94575416/146691416-d070174a-81a6-4dc7-bbb4-c04d5b95e532.png)

   Average Reading Score - 83.7

![9th Grade Reading Scores (original data)](https://user-images.githubusercontent.com/94575416/146691334-201a0476-dde8-4cbf-b864-eb5c09afc7b9.png)

   Average Reading Score - 81.8

![Avg Reading Score (Clean Data)](https://user-images.githubusercontent.com/94575416/146691452-61d51df8-d040-4cb5-808b-5b4e512885f4.png)


## Disctrict Level:

### Math and reading scores by grade

![Math Scores](https://user-images.githubusercontent.com/94575416/146692903-89cdebae-7514-4ccb-955a-824ecb05966a.png)    

![Reading Scores](https://user-images.githubusercontent.com/94575416/146692919-4bb92e88-5234-40df-8e4d-3278d4bfaf42.png)


### Scores by school spending

![Per School Summary](https://user-images.githubusercontent.com/94575416/146692978-32d9c899-fe7e-41d7-955d-eb52c22e4db1.png)

### Scores by school size

![Size Summary](https://user-images.githubusercontent.com/94575416/146693002-4ac1122b-a059-46ec-93a0-8526de68a710.png)

### Scores by school type

![Type Summary](https://user-images.githubusercontent.com/94575416/146693013-c4a031ce-c689-4156-843f-a0a16d78836b.png)


##Summary: 

Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

Math and Reading Scores by Grade:

Thomas High Schools 9th grade math & reading scores set to place a NaN in the place of the grade that was there.
With the new grades in place the total passing math and reading grades for 9th grade are equivalent to failing grades.

Scores by School Spending:

Thomas High School is in the "$630-644" bin.
Removing the scores for 9th grade reduces the "% Passing Math", "% Passing Reading" and "% Overall Passing" scores for this category produces the following:
Original Data: 73, 84, 63
Clean Data: 67, 77, 56

Scores by School Size:

Thomas HS is in the "Medium (1000-2000)" size category.
Removing the scores for 9th grade reduces the "% Passing Math", "% Passing Reading" and "% Overall Passing" scores for this category produces the following:
Original Data: 94, 97, 91
Clean Data: 88, 91, 85

Scores by School Type:

Thomas High School is in the Charter School category.
Removing the scores for 9th grade reduces the "% Passing Math", "% Passing Reading" and "% Overall Passing" scores for this category produces the following:
Original Data: 94, 97, 90
Clean Data: 90	93	87
