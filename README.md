# Pewlett-Hackard-Analysis
## Overview of the analysis

The following analysis was conducted to determine the number of retiring employees per title and identify employees who are eligible to participate in a mentorship program. Afterwards, a report summarizing the analysis was created to help the manager prepare for the "silver tsunami" as many current employees reach retirement age. 

## Results

The Pewlett-Hackard-Analysis was able to create important tables and results that would help the leadership at the company plan accordingly in terms of having to hire a new batch of employees as many employees were approaching the retirement age. Crucial results are displayed as follows along with images describing in detail:

* There is a total of 90,398 retiring employees. 
* "Staff" and "Senior Staff" make up 44.8% of the total number. "Senior Engineer", "Engineer", and "Assistant Engineer" make up 50.2% while the remaining 5% is made of "Technique Leader." The image below shows how the numbers mentioned above were come up with: 

<img width="898" alt="retiring_titles" src="https://user-images.githubusercontent.com/101376325/167323955-d88fe2a9-11c5-4575-84bf-e8c907ebdf63.png">

*  There is a total of 1,940 employees who are eligible to be mentors. The image below shows the input into the query editor and a table showing the first 10 rows; however, 1,940 rows are generated which represents the employees eligible to be mentors: 

<img width="1039" alt="mentorship_eligibilty" src="https://user-images.githubusercontent.com/101376325/167324803-1ae77972-ac69-431a-9b84-c17c079eaedc.png">

* With 1,940 eligible mentors and 90,398 next generation employees, this brings a ratio 1:46.6 which equates to the fact that each mentor will have to be mentoring at least 46 next generation employees.


## Summary

* As seen from the results above, a total of 90,398 vacancies will need to be filled which accounts for 30.1% of the 300,024 employees that we have from the initial employees.csv file. 

* With each mentor expected to mentor at least 46 next generation employees, this can be a little overwhelming for the mentors and it may lead to an ineffective job in mentoring this next group. Extending the eligibility date by a year or two can lower the workload and there may be a higher number of mentors thus effectively mentoring the next generation employees. If the eligibilty includes employees born in 1964 in addition to the initial 1,940 from 1965, the number of mentors jumps to 24,853 which brings a ratio of 1:3.6 which is each mentor has at least 3 next generation employees to mentor as shown in the query editor below:

<img width="954" alt="1964" src="https://user-images.githubusercontent.com/101376325/167327226-dd0a5507-b4c7-4054-830c-91b09a6e2b59.png">

* If the eligibilty extends to 1963, the number of mentors will be 47,933 which is a ratio of 1:1.88 equivalent to roughly each mentor with 2 mentees as shown below: 

<img width="1063" alt="1963" src="https://user-images.githubusercontent.com/101376325/167327707-9133a993-e1aa-4709-a747-6953a4704380.png">

* As seen from above, the conclusion is that for effective training and mentorship, it is important that the eligibilty for mentorship program is extended by at least a year. 