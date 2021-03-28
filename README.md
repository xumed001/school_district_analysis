# School_District_Analysis
## Project Overview
This project is an analysis of 15 differnt high schools within a district. The analysis of this data returns key metrics for each school and presents it in a visual format. The metrics are as follows:
- Top 5 and bottom 5 performing schools, based on the overall passing rate
- The average math score received by students in each grade level at each school
- The average reading score received by students in each grade level at each school
- School performance based on the budget per student
- School performance based on the school size 
- School performance based on the type of school

## Challenge Overview
The school board has notified that the students data show evidence of academic dishonesty. Reading and math grades for Thomas High School ninth graders appear to have been altered, therefore unreliable. The challenge analysis replaces the math and reading scores for Thomas High School with NaNs and keeps the rest of the data intact.

## Results
- After adjusting the district analysis to account for the faulty data the overall district summary has not been affected that much. For example the overall passing percentage has gone down from 65% to 64.9% which is less that 1 points.
- The school summary also largely reamains the same, except for Thomas High School where data removed from 9th graders causes the schools overall passing grade to go down 65% from previous 90%.
- After replacing the Thomas High School's 9th graders scores with only their 10th to 12th graders, the schools overall passing percentage goes back up to 91% relative to other schools in the district.  
- The overall results after replaceing the 9th grade's data will not change scores by school spending, size or school type because the total number of students for Thomas High school is still the same and must be factored into the catagories above regardless of faulty data for their math and reading scores. 

## Summary
In Summary, after replacing reading and math scores for the ninth grade at Thomas High School we see it did not affect the overall district analysis by that much becasue it was only one high school's ninth grade data. However data based on individual school summary reflects the change most accurately, as reaplacing the ninth graders scores with NaNs is equal to taking away roughly 1/4th's of the schools data. When we correct the data to only show students score from 10th to 12th grades and update the school summary we see Thomas High school back on top. After the correction, all data calculated mostly remains the same becasue even though there was faulty data from the 9th graders the student count of Thomas High School is not what's affected.  
