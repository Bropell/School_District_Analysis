# School_District_Analysis
## Analysis Overview
The purpose of this analysis is to use the power of Pandas and Jupyter Notebook to analyze data from many schools within a district. The data must be aggregated in order to analyze the trends in school performance in math and reading. Based off this data, the school board can make better decisions regarding budget allotments. For the challenge specifically, the school board found evidence of academic dishonesty within the math and reading grades from Thomas High School nith graders. Their math and reading scores are to be removed from the data and the school district analysis must be repeated in order to see how the changes affected the overall analysis. 
## Results
https://github.com/Bropell/School_District_Analysis/blob/main/PyCitySchools_Challenge.ipynb

- How is the district summary affected?

Before: ![alt text](https://github.com/Bropell/School_District_Analysis/blob/main/Resources/district_summary_before.png)
After: ![alt text](https://github.com/Bropell/School_District_Analysis/blob/main/Resources/district_summary_after.png)

As seen in the images above, removing the math and reading scores from the Thomas High School ninth graders had little to no affect on the district summary. Everything dropped by tenths of a percent except for the average reading score which remained the same. The total schools, total students and total budget obviously remained the same since ommitting math and reading scores do not affect those parameters.  

- How is the school summary affected?

Before: ![alt text](https://github.com/Bropell/School_District_Analysis/blob/main/Resources/per_school_summary_before.png)
After: ![alt text](https://github.com/Bropell/School_District_Analysis/blob/main/Resources/per_school_summary_after.png)

 As seen in the images above, removing the math and reading scores from the Thomas High School ninth graders also had little to no affect on the school summary. Once again, there is a drop in about a tenth of a percent to several tenths of a percent in average math score, % passing math, % passing reading and % overall passing. On the other hand, the average reading score actually went up by several hundreths of a percent, which is basically negligible. The other parameters remain unchanged for the same reason as mentioned before.

- How does replacing the ninth graders' math and reading scores affect Thomas High School's performance relative to other schools?

Before: ![alt text](https://github.com/Bropell/School_District_Analysis/blob/main/Resources/top_schools_before.png)
After: ![alt text](https://github.com/Bropell/School_District_Analysis/blob/main/Resources/top_schools_after.png)

- How does replacing the ninth-grade scores affect the following:
    - Math and reading scores by grade
    - Scores by school spending
    - Scores by school size
    - Scores by school type
## Summary