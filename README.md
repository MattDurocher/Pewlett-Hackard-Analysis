# Pewlett-Hackard-Analysis
## Overview of the analysis
### Explain the purpose of this analysis.
The purpose of this analysis was to create tables with Bobby for his manager at Pewlett Hackard. The manager wants to have information on employees who are retiring while also having a birth date between January 1, 1952 and December 31, 1955. We also wanted to find out which employees were eligble for mentorship while also being born between January 1, 1965 and December 31, 1965. In total, four tables were created and four csv files were created.
## Results
### Provide a bulleted list with four major points from the two analysis deliverables. Use images as support where needed.
Mentorship Eligibility
- There are 1,549 eligible employees
- Each employee is listed once with their employee number, full name, hire date, retire date, birth date, and title.
- Hilari Morton is the first listed employee
- There are no columns with null or missing data
<img width="734" alt="Screen Shot 2022-09-28 at 11 06 30 PM" src="https://user-images.githubusercontent.com/111014191/192952115-c02fb05d-a8fd-470c-8c41-2917107c3c10.png">

Retiring Titles
- There are seven groups of retiring employees
- The largest group retring is the "Senior Engineer" group
- The smallest group reitring is the "Manager" group
- All types of engineers take up three of the avaiable seven groups and make up 50.09% of all retiring employees
<img width="246" alt="Screen Shot 2022-09-28 at 11 04 42 PM" src="https://user-images.githubusercontent.com/111014191/192951825-8ad3bb22-fdc3-4520-9ebf-521f53ef8aa7.png">

## Summary
### Provide high-level responses to the following questions, then provide two additional queries or tables that may provide more insight into the upcoming "silver tsunami."
- How many roles will need to be filled as the "silver tsunami" begins to make an impact?
  - There are 90,398 employees that will be retiring during the time of the silver tsunami. We can easily break that down by sectioning off a table for each year and, breaking things down by grouping the data by job title and counting it by employee number in the same way that we did to create the retiring_titles table. This would allow us to know exactly how mnay roles to fill each year and what department to hire new employees for by looking at the three unique/new tables.  
- Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?
  - There are 1,549 employees able to act as mentors as found in the mentorship_eligibility table. This will be plenty of employees to go ahead and get the next generation of Pewlett-Hackard employees intergrated into the workplace over the next few years.
