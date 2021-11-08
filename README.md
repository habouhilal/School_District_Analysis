# School_District_Analysis
1. Resources
    . Data Source: election_results.csv
2. Software
    . Python 3.7.9
    . Anaconda
    . Jupyter Notebook

## Overview 
This analysis has a purpose of assisting the school board and super intended to make decisions about the school funding and priorities. This analysis will compare the overall school district performance outcomes. The school board has requested to drop all Math and reading scores for the 9th grade class for Thomas High school dues to suspected academic dishonesty.  After replacing this data with NaN, the school district board would like to compare the results and see how big is the impact of removing the data. 

## District Summary
The district summary results after taking out the Thomas High School Math and Reading scores for the 9th grade were as follows:
- The average reading scores did not change.
- The average math scores decreased from 79% to 78.9%
- The percentage passing Reading did decrease from 86% to 85%.
- The percentage passing Math did decrease from 75% to 74%.
- The percentage Overall Passing decreased from 65% to 64%.

### Original Analysis

<img width="1032" alt="original analysis" src="https://user-images.githubusercontent.com/91625564/140685251-c8c66f55-6ea8-42c8-93ca-2b8c5cc7a8fd.png">

### Analysis After the Removal

<img width="1032" alt="New Analysis" src="https://user-images.githubusercontent.com/91625564/140685311-047a935f-b235-4e94-a8bb-782aeae38cfa.png">


### Top 5 Schools Summary
Taking out Thomas High school 9th grade Reading and Math scores didn't change the fact that this school remain on the top 5 schools in the district. 

<img width="1026" alt="school summary" src="https://user-images.githubusercontent.com/91625564/140685338-b8c878e6-0c30-46e9-8872-0880029efa8e.png">


### Reading scores by Spending
The Overall passing percentage is higher for school with less budget. The performance on Average and passing percenatge is increasing for the schools that has lower budget. 

<img width="837" alt="School by spending " src="https://user-images.githubusercontent.com/91625564/140685931-df8b6269-bfdf-4584-bbde-9089a8a553ee.png">



### Scores by School size
Looking at the performance of schooles based on the size, we can say that the difference is not much from small to Medium size. however when the size is over 2000 the performace is less and all passing percentages decrese. 

<img width="816" alt="school by size" src="https://user-images.githubusercontent.com/91625564/140685430-95680351-a927-47ed-9c99-14321bed4812.png">

### Scores by School type 
Based on the type the charter schools have better performance and higher passing percentages than the district schools. The overall passing percentage difference is significant, %90 for charter and %54 for district. 

<img width="817" alt="school by type" src="https://user-images.githubusercontent.com/91625564/140685470-fc9ecde2-f30a-4416-b5bc-5c76325811cd.png">


## Sammary 
The results of this analysis were not favorizing the overall performance of the district schools. Top five schools were charter including Thomas high school. Dropping the data didn't change much of the overall passing results. However, the impact was seen on the average overall math and reading at Thomas high school.





