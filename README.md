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

![District_Analysis](https://github.com/Super-Manda/School_District_Analysis/blob/main/Resources/District_Analysis.png)

-	How is the school summary affected?

![Average_Scores_in-District](https://github.com/Super-Manda/School_District_Analysis/blob/main/Resources/Average_Scores_in-District.png)


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

  -	**Math and reading scores by grade**

![Math_Reading_by_Grades](https://github.com/Super-Manda/School_District_Analysis/blob/main/Resources/Math_Reading_by_Grades.png)


  -	**Scores by school spending**
    - Regarding spending, there is no change because small and medium funded schools have satisfactory pass rates that suggest a better return on investment.  Had NaNs been counted as failures, that would have altered the overall pass rate from 63% down to 56% for the $631 to $645 spending bracket, where Thomas belongs.
    
  ![School_Spending](https://github.com/Super-Manda/School_District_Analysis/blob/main/Resources/Spending_Per_Student.png)
  
  -	**Scores by school size**
 
    - Regarding the size of the school and its passing rate, small schools have a 90% overall pass rate, medium schools have a 91% pass rate, and large schools have only a 58% pass rate.  Since Thomas was a medium school, leaving the NaNs as failures would have brought down the medium schools to an 85% pass rate, which is still satisfactory.  This suggests that students are more apt to get lost in the shuffle at a larger school regardless.
 
  ![School_Size](https://github.com/Super-Manda/School_District_Analysis/blob/main/Resources/School_Size.png)
  
  
  -	**Scores by school type**

    - After excluding NaNs, there is no difference in scores according to school type.  Had the NaNs been counted as failures, there would have been a slight reduction in the overall pass rate of charter schools (from 90% to 87%) because Thomas was a charter school.  Even so, there would still remain a marked difference between district schools and charter schools in that only 54% of district students pass both math and reading overall.  Charter schools still seem to do a much better job of getting students to pass math specifically.

![School_Type](https://github.com/Super-Manda/School_District_Analysis/blob/main/Resources/School_Type.png)



## 3.	Summary: 

### Highlight of Main Changes on Updated School District Analysis 
- Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
