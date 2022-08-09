# Pewlett-Hackard-Analysis

## Overview of the Analysis

The objective of this project is to prepare for a large number of employees who will be reaching retirement age at the same time. In preparing for the upcoming "silver tsunami" we need to know what titles the retirees hold and whom of these employees would be eligible for our mentorship program to mentor the next generation of employees. With those objectives in mind we had to look at databases of employees with the following information: names, dates of births, titles, and when those titles were held. We then had to join the related databases and create new tables and files to better organize the information.

Please see the three databases created below.

[retiring_titles.csv](./Data/retiring_titles.csv)

[unique_titles.csv](./Data/unique_titles.csv)

[mentorship_eligibility.csv](./Data/mentorship_eligibility.csv)


## Results

After completing the two separate analyses, there are 4 major conclusions that can be achieved.

* Pewlett Hackard is going to soon lose 64% of it's workforce.

* Pewlett Hackard's greatest needs will be in highly technical areas (see image below).

![titles_counts.png](../Data/titles_counts.png)

* Pewlett Hackard's most common mentors will be Senior Staff.

* There are many candidates for the mentorship program (1549 mentors).


## Conclusions

In summary the "silver tsunami" will leave many roles to be filled (specifically 90,398). With only 1549 mentor candidates that makes up only two percent of the workforce that will be retiring. This means that each mentor would need to mentor 58 employees in order to meet the demand. It would be prudent to begin the process of mass hirings as soon as possible. I would recommend to do additional research and expand the search for mentors among younger employees with reasonable tenure to assist in the process.


Please find the SQL code used to draw these conclusions below:

[Employee_Database_challenge.sql](./Queries/Employee_Database_challenge.sql)
