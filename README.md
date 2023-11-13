# sql_challenge
Modue 9 -- SQL Challenge for UC Berkeley Data Analytics Course

In this repository, we are researching former employees of our company using PostgreSQL.  We have taken the data from six CSV files
remaining from the company's employee database and used these six CSVs to create and populate our own SQL database.  From there, 
we have gathered the following requested data:

-The employee number, last name, first name, sex, and salary of each employee.\
-The first name, last name, and hire date for the employees who were hired in 1986.\
-The manager of each department along with their department number, department name, employee number, last name, and first name.\
-The department number for each employee along with that employee’s employee number, last name, first name, and department name.\
-The first name, last name, and sex of each employee whose first name is Hercules and whose last name begins with the letter B.\
-Each employee in the Sales department, including their employee number, last name, and first name.\
-Each employee in the Sales and Development departments, including their employee number, last name, first name, and department name.\
-The frequency counts, in descending order, of all the employee last names (that is, how many employees share each last name).\
\
\
For this project, I had to research two methods that I had not picked up in class.\
\
References:
DATE_PART reference -- https://www.commandprompt.com/education/how-to-use-date_part-function-in-postgresql/#:~:text=DATE_PART()%20is%20a%20built,out%20from%20the%20given%20source.

LIKE method reference -- https://stackoverflow.com/questions/16179802/query-to-retrieve-all-people-with-a-last-name-starting-with-a-specific-letter
