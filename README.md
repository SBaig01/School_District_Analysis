# School_District_Analysis

## Overview of the School District Analysis

### Purpose
Due to suspected academic misconduct, the school district board has asked Maria for additional analysis results. They would like her to repeat the performed analysis but replace all grade 9 results for Thomas High School - Maths and Reading grades, with NaNs, while keeping the rest of the data intact.

## Results

* District Summary: After updating the analysis, the District Summary displays **NaN** for all students from Thomas High School Grade 9 (see below).

    ![District_Summary](https://github.com/SBaig01/School_District_Analysis/blob/52b0895a0b8ed7f02bef68dce794a13ae62836c9/student_data_complete_df.png)

* School Summary: The following changes were noted in the school summary after the update:
   - **Average Math Score:** From *83.418349* to *83.350937*
   - **Average Reading Score:** From *83.848930* to *83.896082*
   - **% Passing Math:** From *93.272171* to *66.911315*
   - **% Passing Reading:** From *97.308869* to *69.663609*
   - **% Overall Passing:** From *90.948012* to *65.076453*
* How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
   - There is no change in the relative performance of Thomas High School compared to others as it ranks second in overall passing grade both before and after the update.


## Summary
* How does replacing the ninth-grade scores affect the following:
   - Math and reading scores by grade: The 9th grade average score for Thomas High School has been replaced by NaN (see below).
        ![Scores by Grade](https://github.com/SBaig01/School_District_Analysis/blob/ea80b59a9a9583e63958ea4d27f7a7b27d69bb26/a.png)
   - Scores by school spending: 
   - Scores by school size: 
   - Scores by school type: 
