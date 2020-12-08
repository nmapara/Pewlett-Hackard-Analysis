# Pewlett-Hackard-Analysis
## Overview of Project
This project is part of module 7 in the Data Science Bootcamp.
The purpose of this project is to develop experience with SQL, creating tables, joins, and conditionals.

## Results
SQL queries were developed to answer two specific questions.  Firstly, we wanted to know the number of employees that would be retiring based on their job title.  Secondly, we wanted to identify the employees who would be eligible for a mentorship program.

Figure 1 below shows the table generated to answer the question of who will be eligible for retirement in the coming term.  
-	As we can see, there are 29, 414 senior engineers who may retire and leave a drastic technical vacuum in the company.  We do have to worry about a ‘silver tsunami’ for these engineers.
-	Only 2 Managers will be eligible for retirement.  The leadership team is young, and we don’t need to worry about a ‘silver Tsunami’ for them.

![Graph](/Data/retiring_titles.PNG)

Figure 2 below answers the question of employees eligible for mentorship.  1549 employees were identified for the mentorship.  
Although there are nearly 90, 000 staff who could potentially retire, and only 1549 employees were identified for mentorship.  We can conclude that:
-	The company will need to broaden it’s requirements for enrolling in the corporate mentorship program, and
-	The company may need to engage in an immediate hiring effort to fill the vacancies left by the retiring employees.

![Graph](/Data/mentorship_eligibilty.PNG)

### Summary
As the ‘silver tsunami’ makes an impact, over 90 000 roles will need to be filled.  
And we have only identified 1549 mentors for the next generation.  
-	We will need to broaden our hiring and mentor eligibility requirements
-	It would be helpful to understand what roles the 1549 mentors will fulfill?  Are they engineers or managers?  It would be easy to run a table to extract this data.
-	
-	It would be helpful to do a statistical analysis and find out whether the expected retirement volume will be evenly spread out over a few years, or whether the retirement will occur in large volumes in the early years.  A regression analysis to identify the distribution of ages in the eligible retiree population would be helpful.

