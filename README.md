# School District Analysis
## Overview of the school district analysis
School District Analysis had been done before, but the school board found the evidence of acedemic dishonesty. Specifically, reading and math grades for Thomas High School ninth graders appear to have been altered, so Mario asked me to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. I will repeat the School District Analysis again to compare how it affects the overall analysis

## Results
- How is the "district summary" affected?
    - Because some grades are deleted, average math and reading scores change.
    - Passing student counts change, so that passing percentages also change.
    - 'Total Students' and 'Budget' remains the same.
    
 ![School_District_Analysis_before](Resourses/School_District_Analysis_before.png)
 ![School_District_Analysis_after](Resourses/School_District_Analysis_after.png)

- How is the "school summary" affected?
    - 'Total Students' remains the same.
    - However, students in 9th grade are excluded, so total student count gets less. Math passing rate, reading passing rate and overall passing rate change.
    ![school_summary_before](Resourses/school_summary_before.png)
    ![school_summary_after](Resourses/school_summary_after.png)
    
- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
    - THS performance becomes No.2 school.
    ![top5](Resourses/top5.png)

- How does replacing the ninth-grade scores affect the "Math and reading scores by grade"
    -  9th grade in THS becomes "NaN, while others remain the same.
    ![THS_9th](Resourses/THS_9th.png)

- How does replacing the ninth-grade scores affect the "Scores by school spending"
    - THS belongs 630-644 range, so for this row, passing rates and average scores change. However, the change is small, after formatting, the changes cannot be noticed.
    ![before](Resourses/spending_before.png)
    ![after](Resourses/spending_after.png)

- How does replacing the ninth-grade scores affect the "Scores by school size"
    - THS is a medium size school, so for medium size school row, passing rates and average scores change. However, the change is small, after formatting, the changes cannot be noticed.
    ![before](Resourses/size_before.png)
    ![after](Resourses/size_after.png)

- How does replacing the ninth-grade scores affect the "Scores by school type"
    - THS belongs to "Charter", so	for "Charter" row, passing rates and average scores change. However, the change is small, after formatting, the changes cannot be noticed.
    ![before](Resourses/type_before.png)
    ![after](Resourses/type_after.png)

## Summary
after reading and math scores have been replaced to "NaN", I do not count 9th grade in THS any more, so it makes some major changes

- The replacement will mainly affect:
    - Average reading score and math score for THS
    - Reading, math and overall passing rates for THS
    - Scores for 9th grade
    - The average scores and passing rates of the group which THS belongs to, no matter how the data will be summarized
    
