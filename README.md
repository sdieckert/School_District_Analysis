# School_District_Analysis
## Project Overview
The school board has requested an analysis of the district's math and reading performance. Combining school data, which includes school type, student size and budget, with student data allows for a summary level analysis of the district, by individual schools and grade level. Evidence of academic dishonestly was discovered for Thomas High School's ninth grade scores, so while the issue is being investigated, it's been decided to omit Thomas High Schools' ninth grade reading and math scores by replacing their scores with NaNs. In doing so, overall summaries of averages and percentages of passing grades needs to be revised. 

## Resources
- Data Source: schools_complete.csv, students_complete.csv
- Software: Python 3.7.6, Visual Studio Code, 1.66.2

## Challenge Overview

Challenge consists of two technical analysis deliverables and a written report to present your results. Submit the following:

### Deliverable 1: Replace ninth-grade reading and math scores

- Step 1: Install numpy using conda install numpy or pip install numpy. Import numpy as np.
- Step 2: Use the loc method on the student_data_df to select all the reading scores from the 9th grade at Thomas High School and replace them with NaN
- Step 3: Refactor the code in Step 2 to replace the math scores with NaN
- Step 4: Check the student data for NaN's
- Step 5: Verify that your student_data_df has NaA for both math and reading for Thomas High School

### Deliverable 2: Repeat the school district analysis
- Step 1: Get the number of students that are in ninth grade at Thomas High School. These students have no grades. 
- Step 2: Subtract the number of students that are in ninth grade at Thomas High School from the total student count to get the new total student count.
- Step 3: Calculate the passing percentages with the new total student count.
- Step 4: Calculate the overall passing percentage with new total student count.

Create DataFrame and verify that average and percentage metrics changed due to change in total students. 

- Step 5:  Get the number of 10th-12th graders from Thomas High School (THS).
- Step 6: Get all the students passing math from THS
- Step 7: Get all the students passing reading from THS
- Step 8: Get all the students passing math and reading from THS
- Step 9: Calculate the percentage of 10th-12th grade students passing math from Thomas High School. 
- Step 10: Calculate the percentage of 10th-12th grade students passing reading from Thomas High School.
- Step 11: Calculate the overall passing percentage of 10th-12th grade from Thomas High School. 
- Step 12: Replace the passing math percent for Thomas High School in the per_school_summary_df.
- Step 13: Replace the passing reading percentage for Thomas High School in the per_school_summary_df.
- Step 14: Replace the overall passing percentage for Thomas High School in the per_school_summary_df.

Verify Thomas High School metric changes. Print df.

Next, complete the following steps for school district analysis using the remaining steps that are provided in the starter code.

The top 5 and bottom 5 performing schools, based on the overall passing rate.
The average math score for each grade level from each school.
The average reading score for each grade level from each school.
The scores by school spending per student, by school size, and by school type.

## Results

### Deliverable 1

The reading and math scores for the ninth graders in Thomas High school are replaced with NaNs.

NaN.png

<Insert NaA>

### Deliverable 2

##### District Summary

##### Original Summary

<Insert Original Summary>
##### Revised Summary

<Insert Revised Summary>

The following metrics were affected by the change in Thomas High School ISD's ninth grade scores being replaced by NaN.

- Total Student Count For Calculations
The original student dataset consisted of 39,170 students. After using the loc method to isolate the 461 Thomas High School ninth graders, new student count to use in percentage metrics changed to 38,709.

- Average Math Score
The overall average math score for the district dropped 0.1 points from 79.0 to 79.9. 

- Average Reading Score
The overall average reading score for the district remained the same.

- Percentage Passing Math
The overall percentage of students passing math dropped .2 points from 75 to 74.8.

- Percentage Passing Reading
The overall percentage of students passing reading dropped .3 points from 86 to 85.7.

- Percentage Passing Overall
The overall percentage passing dropped from .1 points from 65 to 64.9.

#### School Summary
##### Original School Summary
<<Insert Original Summary>>
##### Revised School Summary
<Insert Revised Summary>

The following metrics were affected by the change in Thomas High School ISD's ninth grade scores being replaced by NaN.

- Total Student Count
The original student dataset for Thomas High School consisted of 1,635 students. After using the loc method to isolate the 1,174 Thomas High School ninth 10th, 11th and 12th graders, it became the new student count for the metrics.

- Average Math Score
The overall average math score for Thomas High School dropped 0.07 points from 83.42 to 83.35. 

- Average Reading Score
The overall average reading score for Thomas High School increased by .05 points from 83.85 to 83.90.

- Percentage Passing Math
The overall percentage of Thomas High School students passing math dropped .1 points from 93.27 to 93.19.

- Percentage Passing Reading
The overall percentage of Thomas High School students passing reading dropped .29 points from 97.31 to 97.02.

- Percentage Passing Overall
The overall percentage of students at Thomas High School passing dropped from .32 points from 90.95 to 90.63.

#### Top 5 Performing Schools

#### Bottom 5 Performing Schools

#### Average Math Score for each grade from each school

#### Average Reading Score for each grade from each school

#### The scores by school spending per student, by school size and by school type

## Summary

The 4 main changes that resulted in changing Thomas High School to NaNs.
- The districts overall math average, percentage passing math and reading and percentage of overall passing dropped a min of .1 to a max of .3 points.

- Thomas High School's math average, percentage passing math and reading and percentage of overall passing dropped but their average reading score increased slightly.

- Replacing Thomas High School's 9th grade scores had no affect on the school being ranked 2nd overall in the district.

- Replacing Thomas High School's 9th grade scores gave them an NaN when comparing averages of math and reading for each grade from each school.

- Replacing Thomas High School's 9th grade scores had no affects on the summarization of scores by school spending per student, school size and school type.



