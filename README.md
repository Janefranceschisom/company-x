# Company-x

# INTRODUCTION
Company X is non existing company,the name was just coined out by me for the purpose of learning. It consists of four datasets which were imported 
through csv/text format. i then cleaned the datasets using the power query which was later applied and was taken the the report view for 
visualization using Power bi desktop.

# KPI

1. Find and visualize
   a) The number of employees
   b) The average age as at when hired
   c) The total number of the departments
   d) The average salary of each employee over the year
   e) Number of male and female employees
   f) Average salary of each department
   g) Average salary of the two genders
   h) Number of employees hired each year
   i) The top 10 highest salary earners and their fullname


   # VISUALIZATION

   The dataset that was used are salaries,employees,dept_emp,departments. the salaries dataset was cleaned and the average salary was deducted using the
   group by in the power query section . the new formed dataset was later used to perform some DAX calculation.

    ![Screenshot (11)](https://github.com/Janefranceschisom/company-x/assets/140454293/16401ed2-15f4-4b1a-b14a-bcbf9a52ba3d)

   A) In the finding the number of employees , the employees dataset was used and the `count distinct` function was used to enact the individual numbers.
   which after the card view was used to visualize the number of employees.
   B) In finding the average age as at when hired , a new column was formed in which the `datediff` function was use to get the actual age from their birthdate and hiredate.
   which was later visualized with a card view.
   C) The total number of the departments was gotten from the department dataset and was viewed with card view.
   D) The average salary of each employee was gotten from the average data dataset.
   E) The number of male and female employees was calculated using the new measure format to calculate and filter the number of the genders.
   F) The average salary of each department was visualized with bar chart.
   G) Average salary of the two genders was visualized with Donut chart.
   H) Number of employees hired each year was visualize with a line chart.
   I)  The top 10 highest salary earners and their fullname was visualized with a table  and those that earned more than 142,000 was highlighted with conditional format.


   # CONCLUSION

   Company X stakeholders wanted to know the insights from their company's welfare so as to know the resources they are putting into the company and the number of workers they have,
   which will make them make informed decision about the company.
