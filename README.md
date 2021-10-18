## Pewlett-Hackard-Analysis
### 1. Overview of the Analysis

We analyzed data for a company called Pewlett-Hackard in a data analytics project. The purpose of this project was to determine the number of employees who are eligible for retiring and their retirement time is forthcoming. might be retiring soon at a large company called Pewlett-Hackard. This will help Pewlett-Hackardthe forecast the total number of retirement packages they might have to offer. Furtheremore, they can coordinate with their recruitment department to identify which positions will need to be filled. Because of Pewlett-Hackard's large size, a sudden surge in nomber of retiring employees can be detrimental to their core business and may result in leaving a huge portion of their workforce unavailabe. The goal of this project is to help Pewlett-Hackard plan accordingly and avoid any damage to their business due to retirement crisis.

### 2. Data Source
We were provided total of (6) CSV files containing variable information about employees, departments, titles, salaries, and management. We decided to use PostGress database language to work through analyzing the data. The data that was provided to us was assumed clean. Initially, we reviewed all CSV files to identify the primary keys and the relationship between these data. 

### 3. Results
We combined several tables using join techniques in SQL programming language and then filtered the data to only show certain employees who were born between 1952-1955. After that, We organized the combined table by job title, and the total of potential retirees was calculated. A second table was constructed from the original six datasets to identify employees born in the year 1965 who are still with Pewlett-Hackard. These employees are potential candidates for a mentorship program, where a retiring employee trains them to fill the position they are leaving.

#### Retirement by title
The most urgent item Pewlett-Hackard needs to pay attention  is the fact that 29414 senior engineers are in the retiring list. This means a noticable budget should be dedicated towards paying retirement costs for those senior engineers. There are also 14,222 employees with the title of Engineer who also meet the criteria. Pewlett Hackard needs to put into place a plan to recruit seneior level engineers to fill these roles. One option would be internal recruiting, but considering the fact that there are also a noticable amount of junior level engineers ready to be retired makes this less reasonable. Therefore, an urgent plan for external recruiting seems like a reasonable solution.

Middle management will be unaffected by possible retirement. There are only two employees with the title of manager who meet the criteria for potential retirement. Pewlett-Hackard can look to existing managers to potentially fill Senior Leadership positions that might open. There are 28,254 employees with the title of Senior Staff who meet the retirement criteria.
Our data also shows that there are 4 employees with manager title that are ready for retirement. We recommend these rolls be filled by internal applicants.
![image](https://user-images.githubusercontent.com/86033316/137658543-451a29ad-93a8-4941-9963-52d587f82589.png)

#### Mentorship 
One solution for Pewlett Hackard is to start a mentorship program to fill in the upcoming job opennings due to retirement of employees. We generated a Mentorship table that contains information for employees with an birthdate between 1965 and 1966 who are currently employed. After analysis this information, we think that The mentorship program is not capable of  filling all the oprnnings. Our data indicates that there are only 1,549 employees who are ellgible for being mentored. With 14,222 mid-level engineering positions opening, this would not even satisfy the need for that single job title openinngs.

![image](https://user-images.githubusercontent.com/86033316/137658577-4c9855af-308a-46b5-98ad-22b399cb8ab6.png)


### 4. Summary
Questions
How many roles will need to be filled as the "silver tsunami" begins to make an impact?
90,398 positions will need to be filled.


Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?

Unfortunately not. The total count of employees that are capable of mentoring next generation of employees is 1,549 which can fill about 1.7% of all 90,398 upcoming empty roles. This means in total, for every 100 new emolyees, there are 1.7 mentors. 


### 4. Our Recommendation 
We believe Pewlett Hackard can have more mentors by Widening the range of employees eligible for the mentorship program. This will help find more internal options to fill positions. Internal recruiting is usually prefered to external employment because those employees are already vetted and familiar with company;s culture and methods of procedure. 

We also recommend that Hewlett-Packard considers other performance criteria for determining who can mentor other new hires. There may be a possibility that an Engineer with even less amount of experience can mentor other new hires. It all goes to mentor's performance and it is not the count of years that person has worked that determines he or she can mentor other new hires.
