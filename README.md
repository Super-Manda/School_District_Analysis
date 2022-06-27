# Overview of the school district analysis: 🧑‍🏫

## 1. Purpose

This is a large data analysis of 15 schools in a district, some of which are district schools, and some of which are charter schools.  In this report, data is no longer available for 9th graders at Thomas High School due to a cheating scandal at that charter school.  The first part of this data analysis was to replace the previously recorded scores of the 9th graders with NaN scores.  After checking that this was successful, the analysis was able to continue.

![Checked_for_THS9_NaNs](https://github.com/Super-Manda/School_District_Analysis/blob/main/Resources/Checked_for_THS9_NaNs.png)

### The district wishes to know more about: 
- A high-level snapshot of the district's key metrics, presented in a table format
- An overview of the key metrics for each school, presented in a table format
- Tables presenting each of the following metrics:
  - Top 5 and bottom 5 performing schools, based on the overall passing rate
  - The average math score received by students in each grade level at each school
  - The average reading score received by students in each grade level at each school
  - School performance based on the budget per student
  - School performance based on the school size 
  - School performance based on the type of school

## 2.	Results: 

### Affect on District and School Summaries
-	How is the district summary affected?
-	How is the school summary affected?

### Affect on Thomas High School's Standing
-	**How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?**

-When the NaNs were counted as failing the 9th graders' math and reading scores, Thomas High School would have gone from being ranked #2 in the district on overall pass rate to being ranked #8; however, they re-adjusted the statistics to exclude the NaNs.

- **Original Stats on Thomas High School**
  -  Overall Pass Rate: 90.95%
  - Math Pass Rate: 93.27%
  - Reading Pass Rate: 97.31%
  - Ranked: #2 after Cabrera High School

- **Stats on Thomas High School when NaNs Count as Failures**
  - Overall Passing Rate: 65.08%
  - Math Passing Rate: 66.91%
  - Reading Passing Rate: 69.66%
  - Ranked: #8 after Cabrera, Griffin, Wilson, Pena, Wright, Shelton, and Holden High Schools

![THS9_NaNs_Counted_As_Fail](https://github.com/Super-Manda/School_District_Analysis/blob/main/Resources/THS9_NaNs_Counted_As_Fail.png)


**However, when the statistics are re-adjusted to only include grades 10 to 12 in the statistic, the adjustment results in no change to Thomas’ standing in the #2 rank.**  

- **Stats on Thomas High School when Discounting the NaNs**
  - Overall Pass Rate: 90.63%
  - Math Pass Rate: 93.19%
  - Reading Pass Rate: 97.02%
  - Ranked: #2 after Cabrera High School

![Best_Worst_Schools_Combined](https://github.com/Super-Manda/School_District_Analysis/blob/main/Resources/Best_Worst_Schools_Combined.png)


### Affect of NaNs on Grade 9 Metrics
-	How does replacing the ninth-grade scores affect the following:
  -	Math and reading scores by grade
  -	Scores by school spending
  -	Scores by school size
  -	Scores by school type

![Math_Reading_by_Grades](https://github.com/Super-Manda/School_District_Analysis/blob/main/Resources/Math_Reading_by_Grades.png)


## 3.	Summary: 

### Highlight of Main Changes on Updated School District Analysis 
- Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
