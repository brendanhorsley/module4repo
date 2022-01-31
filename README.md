# School District Analysis

## Overview
The data worked on in this analysis consisted of data relating to high schools. 
This data included the english and reading scores of students throughout multiple high schools.
It was discovered that in the 9th grade classes of "Thomas High School", there was an instance of academic dishonesty that altered the data.
Maria reached out to have the 9th grade data from this school removed without disrupting any of the other data.
After this data is removed the new completed data was reanalyzed to discover how the removal of this grade level affected the overall data.

## Results
Below is the summary of the data before the removal of the 9th grade class from Thomas High.
Most noticable is the low pass percentages for this school.
![Summary_Before_Removal](https://user-images.githubusercontent.com/96553988/151736830-13cba36e-1735-4d7a-8d29-e8923475bc9b.png)


The 2nd picture (below), is of the summary of the data after the 9th grade class had been removed.
![Summary_After_Removal](https://user-images.githubusercontent.com/96553988/151736790-9dffdcfe-130f-4053-b840-7063bb042e49.png)

The removal of data chose to not delete the rows of the ninth grade class but instead to remove their values from the calculation of grades.

How our removal effected the data:
* Total Students: no effect
* Total School Budget: no effect
* Per Student Budget: no effect
* Avg Reading Score: no effect
* Avg Math Score: no effect
* % Passing Math: recalculated with new data creating an increase in the number of students who passed from Thomas High School
* % Passing Reading: recalculated with new data creating an increase in the number of students who passed from Thomas High School
* % Passing Overall : recalculated with new data creating an increase in the number of students who passed from Thomas High School

Below is the updated math scores by grade: 
![math_scores_grade](https://user-images.githubusercontent.com/96553988/151740953-2ea2fa0b-5adf-4aa5-ae5a-71bacc59fe3a.png)

Here is the data frame for the recalculated scores by spending:
![scores_by_spending](https://user-images.githubusercontent.com/96553988/151740718-22337ebe-e494-451e-8435-b97ec12e5caf.png)

Here is the new data frame for the scores by school size:
![scores_by_size](https://user-images.githubusercontent.com/96553988/151740825-884d9b24-65c3-4c6b-927b-11785df34db1.png)

And Lastly here is the updated score by type:
![score_by_type](https://user-images.githubusercontent.com/96553988/151741025-7c5e57e5-26d8-44e7-9c6f-d311ed31397d.png)



# Analysis
Changes displayed after data removal:
* The percentage of students who passed math incresed from 66.9% to 93.2%
* The percentage of students who passed reading increased from 69.7% to 97.0%
* The overall passing percentage increased from 65.1% to 90.6%
