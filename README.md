# School-District-Analysis
## Overview of Project
The school board has notified us the students_complete.csv file shows evidence
of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear
to have been altered. Although the school board does not know the full extent of the academic dishonesty 
they want to uphold state-testing standards and have turned to Maria for help. They have have asked me to replace 
the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once
I've replaced the math and reading scores, they would like me to repeat the school district analysis that
I did in this module and write up a report to describe how these changes affected the overall analysis.
## Results
![School Data before the changes](https://user-images.githubusercontent.com/106290370/175223352-bdce100e-822e-4b4a-aa8a-e0389ba6b1d2.PNG)
Before the data alteration
![School Data after the changes](https://user-images.githubusercontent.com/106290370/175223383-62055c3c-fa94-4489-bd36-58cb23eb9e34.PNG)
After the data alteration

- How is the district summary affected?

Due to the removal of 9th grade THS testing grades, we can see that for the entire district average math score was lowered by .1 
while the average reading score stayed the same. We can also see that the passing math percentage went down by .2% and
passing reading percent went down by .3% which results in a decreases the overall passing percentage by just .1% for the entire district.    

- How is the school summary affected? How does replacing the ninth graders’ math and reading scores affect Thomas 
High School’s performance relative to the other schools?

Removal of the certian THS test scores didn't have an affect on it's ranking of overall passing percentage. THS still remains
the 2nd best school in the entire district. In fact, with removal of 9th grade test score the average reading score increased 
by .05 while other values took a slight decrease like math,reading, and overall passing percentage. 

- How does replacing the ninth-grade scores affect the following:
	- Math and reading scores by grade
  	
    No change
	- Scores by school spending
	 
   For schools that spend $631 - $645 per student, we see a slight increase in overall passing percentage
	- Scores by school size
	  
    No change 
	- Scores by school type
	  
    No change
## Summary
The removal of Thomas High School 9th grade test scores didn't have an affect that many would assume. Due to the population of 
9th graders at Thomas High School being so small compared to the rest of students in the district, lots of the datapoints were not affected
or only altered by 3% or less. The overall passing percentage for the entire district decreased by 1%, Thomas high school maintained there
position rank in overall passing percentage even though it decreasing by .30%, and for schools that spend $631 - $645 per student, the (which THS does)
overall passing percentage only decreased by .10%. 
