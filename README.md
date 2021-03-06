# Challenge Overview

Remove the ninth-grade math and reading scores from Thomas High School and keep all other data associated with ninth-grade students and Thomas School intact.

After Replacing the scores, answer perform the following tasks.

- How is the district summary affected?
- How is the school summary affected?
- How does replacing the ninth graders’ math and reading scores affect -Thomas High School’s performance, relative to the other schools?
- How does replacing the ninth-grade scores affect the Math and Reading Scores by Grade, Scores by School Spending, Scores by School Size, and Scores by School Type? 

## Resourses
- Data Source: schools_complete.csv and clean_students_complete.csv
- Software: Python 3.7.6:: Anaconda, Inc., Jupyter Notebook 6.0.3

# Summary

Upon discovery of inaccuracies in the test scores of Thomas High School’s 9th grade class there was need to re-evaluate the impact upon the district and update data. Thomas High School’s 9th grade consisted of 461 students, which represents 28% of total Thomas High School, and about 1% of the total district population. Overall the average score across the district remained relatively the same, however the passing percentiles all dropped significantly. This is due to the idea that the average score is based on scored tests, this ignoring Thomas High School’s 9th grade. However passing percentiles take into account all students. The adjustment of Thomas High School’s 9th grade scores affected their district ranking, moving them from #2 down to #8

### Detailed Analysis.

Thomas High School’s 9th Grade class consists of 461 Students. This makes up 28% of Thomas High Schools total student population, and about 1% of the district’s overall student population.


#### District Summary

District Summary before adjustments:

|   | Total Schools | Total Students | Total Budget   | Average Math Score | Average Reading Score | % Passing Math | % Passing Reading | % Overall Passing |
|---|---------------|----------------|----------------|--------------------|-----------------------|----------------|-------------------|-------------------|
| Before | 15            | 39,170         | $24,649,428.00 | 79.0               | 81.9                  | 75             | 86                | 65                |
| After | 15            | 39,170         | $24,649,428.00 | 78.9              | 81.9                  | 74             | 85                | 64                |

The district summary dropped by one point in a few areas. The average math score dropped by .1. The passing math percentage, the passing reading percentage, and the overall passing percentage all dropped by 1 point.


#### Thomas High School Summary

Thomas high School Summary Before and After grade adjustment.

|   | Rank | School Type | Total Students | Total School Budget | Per Student Budget | Average Math Score | Average Reading Score | % Passing Math | % Passing Reading | % Overall Passing |
|---|---|---|---|---|---|---|---|---|---|---|
| Before  | #2| Charter     | 1635| $1,043,130.00| $638.00| 83.418349| 83.848930| 93.272171| 97.308869| 90.948012|
| After   | #8| Charter     | 1635| $1,043,130.00| $638.00| 83.350937| 83.896082| 66.911315| 69.663609| 65.076453|

Thomas High School's adjustment had no negative impact on the scores of any other school. For Thomas High School, the following occurred:

- Average readings score went up from 83.85 to 83.90
- Average math score went down from 83.42 to 83.35

This is because the average only utilizes scores other than the 9th grade class.

- The passing math score dropped from 93.3% to 66.9%
- The passing reading score dropped from 97.3% to 69.7%
- The overall passing score dropped from 90.9% to 65.0%

This because the passing percentile takes into account all students, including the affected 9th grade class.

This change impacted the schools's overall ranking in the district, moving it from the #2 position down to the #8 position.

The Math and reading scores for all of the schools except for Thomas High School remained the same. For Thomas high school, the Math and reading scores for 10th, 11th, and 12th grades remained the same. The scores for the 9th grade class were replaced with Nan- Null- meaning no score.

#### Scores by School Spending Per Student

Thomas High School falls into the $630 - $644 spending range; 

- The average scores stayed the same, the passing percentages dropped:
- Passing math went from 73 to 67
- Passing reading went from 84 to 77
- Overall passing went from 63 to 56

#### Scores by School Size

Since Thomas High School was a Medium school; 

- The average math and reading scores stayed the same, however the Passing percentages dropped:
- Passing math went from 94 to 88
- Passing reading went from 97 to 91
- Overall passing went  from 91 to 85
