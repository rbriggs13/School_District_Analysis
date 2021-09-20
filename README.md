# School District Analysis
## Overview

The purpose of this analysis was to use the data from the test scores in the district in order to determine budgeting and other allocation of resources for the next school year. It should be noted that this analysis was performed twice, once with all the data and once without the 9th grade scores from Thomas High School as there was a possibility of academic dishonesty.

## Results
### District Summary
The original district summary is shown below:
![District Summary Original](https://user-images.githubusercontent.com/87343629/134065085-6024a3d6-94c8-48e8-b5d8-be89fe541544.png)
Next is the district summary without the scores from the Thomas High School 9th graders:
![District Summary Fixed](https://user-images.githubusercontent.com/87343629/134065150-662f2928-6fac-48e4-89aa-535ddf1124d3.png)
This data shows that the scores did effect the data albeit only slightly. As almost every category shows very slight drops in their value.
### School Summary for Thomas High School
- The specifics values of Thomas High School remained largely unchanged after the data points for the 9th grade were removed once everything was taken into account.
- As a result this did not affect Thomas High School's standing in the district keeping its position as the second best school in the district.
- By grade obviously the 9th grade scores were no longer taken into account so that aspect was changed but the other grades were unaffected.
- The scores by spending, size, and school type were all also unaffected.
## Summary
Several changes had to be made to the analysis in order to get the correct numbers with the removal of the scores for the Thomas High School 9th graders. The changes are:
- The total amount of students overall had to be changed as to not affect the averages by using too many students
- The total amount of students for Thomas High School 10th-12th grade had to be calculated in order to get the correct scores
- The 9th grade scores for Thomas High School had to be changed to NaN within the data frame itself
- The data also had to be specifically sorted to find the 9th graders from Thomas High School
