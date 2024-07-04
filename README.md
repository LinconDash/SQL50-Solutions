# SQL50-Solutions
- This repository has all the solutions of SQL50 Study Plan from Leetcode. 
- Users can use it to get some reference on how to solve SQL questions present in the study plan if they are preparing for the interviews where SQL is a crucial topic. 
- The solutions are present in three separate directories based on the difficulty level of Leetcode tags such as (Easy, Medium, Hard) 
- All of the 50 questions are listed below with thier problem statement, also thier `solution hint`, use those hints and solve them. 
- If you still find difficulties then please check out the solutions present in the directories 

#### Note : All the solutions are in MySQL


## Problem Statements
### 1757. Recyclable and Low Fat Products
Write a solution to find the ids of products that are both low fat and recyclable. \
Return the result table in any order.
- Solution Hint : AND operator

### 584. Find Customer Referee
Find the names of the customer that are not referred by the customer with id = 2. \
Return the result table in any order.
- Solution Hint : WHERE clause

### 595. Big Countries
A country is big if:
- it has an area of at least three million (i.e., 3000000 km2), or
- it has a population of at least twenty-five million (i.e., 25000000)

Write a solution to find the name, population, and area of the big countries. \
Return the result table in any order.
- Solution Hint : OR operator

### 1148. Article Views I
Write a solution to find all the authors that viewed at least one of their own articles. \
Return the result table sorted by id in ascending order.
- Solution Hint : ORDER BY clause

### 1683. Invalid Tweets
Write a solution to find the IDs of the invalid tweets. \
The tweet is invalid if the number of characters used in the content of the tweet is strictly greater than 15. \
Return the result table in any order.
- Solution Hint : LENGTH function

### 1378. Replace Employee ID With The Unique Identifier
Write a solution to show the unique ID of each user, If a user does not have a unique ID replace just show null. \
Return the result table in any order.
- Solution Hint : LEFT JOIN

### 1068. Product Sales Analysis I
Write a solution to report the product_name, year, and price for each sale_id in the Sales table. \
Return the resulting table in any order.
- Solution Hint : LEFT JOIN

### 1581. Customer Who Visited but Did Not Make Any Transactions
Write a solution to find the IDs of the users who visited without making any transactions and the number of times they made these types of visits. \
Return the result table sorted in any order.
- Solution Hint : LEFT JOIN / GROUP BY / ORDER BY

### 197. Rising Temperature
Write a solution to find all dates' Id with higher temperatures compared to its previous dates (yesterday). \
Return the result table in any order.
- Solution Hint : DATEDIFF function

### 1661. Average Time of Process per Machine
There is a factory website that has several machines each running the same number of processes. Write a solution to find the average time each machine takes to complete a process. \
The time to complete a process is the 'end' timestamp minus the 'start' timestamp. The average time is calculated by the total time to complete every process on the machine divided by the number of processes that were run. \
The resulting table should have the machine_id along with the average time as processing_time, which should be rounded to 3 decimal places. \
Return the result table in any order.
- Solution Hint : INNER JOIN / GROUP BY

### 577. Employee Bonus
Write a solution to report the name and bonus amount of each employee with a bonus less than 1000. \
Return the result table in any order.
- Solution Hint : LEFT JOIN / OR operator

### 1280. Students and Examinations
Write a solution to find the number of times each student attended each exam. \
Return the result table ordered by student_id and subject_name.
- Solution Hint : LEFT JOIN / CROSS JOIN / GROUP BY / ORDER BY

### 570. Managers with at Least 5 Direct Reports
Write a solution to find managers with at least five direct reports. \
Return the result table in any order.
- Solution Hint : JOIN / GROUP BY / HAVING

### 1934. Confirmation Rate
The confirmation rate of a user is the number of 'confirmed' messages divided by the total number of requested confirmation messages. The confirmation rate of a user that did not request any confirmation messages is 0. Round the confirmation rate to two decimal places. \
Write a solution to find the confirmation rate of each user. \
Return the result table in any order.
- Solution Hint : LEFT JOIN / GROUP BY / IFNULL function / AVG function / ROUND function

### 620. Not Boring Movies
Write a solution to report the movies with an odd-numbered ID and a description that is not "boring". \
Return the result table ordered by rating in descending order.
- Solution Hint : WHERE / ORDER BY

### 1251. Average Selling Price
Write a solution to find the average selling price for each product. average_price should be rounded to 2 decimal places. \
Return the result table in any order.
- Solution Hint : LEFT JOIN / GROUP BY

### 1075. Project Employees I
Write an SQL query that reports the average experience years of all the employees for each project, rounded to 2 digits. \
Return the result table in any order.
- Solution Hint : LEFT JOIN / GROUP BY

### 1633. Percentage of Users Attended a Contest
Write a solution to find the percentage of the users registered in each contest rounded to two decimals. \
Return the result table ordered by percentage in descending order. In case of a tie, order it by contest_id in ascending order.
- Solution Hint : JOIN / GROUP BY

### 1211. Queries Quality and Percentage
We define query quality as:
- The average of the ratio between query rating and its position.

We also define poor query percentage as:
- The percentage of all queries with rating less than 3.

Write a solution to find each query_name, the quality and poor_query_percentage. \
Both quality and poor_query_percentage should be rounded to 2 decimal places. \
Return the result table in any order.
- Solution Hint :  GROUP BY / Agg. functions

### 1193. Monthly Transactions I
Write an SQL query to find for each month and country, the number of transactions and their total amount, the number of approved transactions and their total amount. \
Return the result table in any order.
- Solution Hint :  GROUP BY / Agg. functions

### 550. Game Play Analysis IV
Write a solution to report the fraction of players that logged in again on the day after the day they first logged in, rounded to 2 decimal places. In other words, you need to count the number of players that logged in for at least two consecutive days starting from their first login date, then divide that number by the total number of players.
- Solution Hint :  Window function

### 2356. Number of Unique Subjects Taught by Each Teacher
Write a solution to calculate the number of unique subjects each teacher teaches in the university. \
Return the result table in any order.
- Solution Hint :  GROUP BY

### 1141. User Activity for the Past 30 Days I
Write a solution to find the daily active user count for a period of 30 days ending 2019-07-27 inclusively. \
A user was active on someday if they made at least one activity on that day. \
Return the result table in any order.
- Solution Hint :  GROUP BY / DATEDIFF function

### 1070. Product Sales Analysis III
Write a solution to select the product id, year, quantity, and price for the first year of every product sold. \
Return the resulting table in any order.
- Solution Hint : Subquery / GROUP BY

### 596. Classes More Than 5 Students
Write a solution to find all the classes that have at least five students. \
Return the result table in any order.
- Solution Hint : GROUP BY / HAVING

### 1729. Find Followers Count
Write a solution that will, for each user, return the number of followers. \
Return the result table ordered by user_id in ascending order.
- Solution Hint : GROUP BY / ORDER BY

### 619. Biggest Single Number
A single number is a number that appeared only once in the MyNumbers table. \
Find the largest single number. If there is no single number, report null. 
- Solution Hint : Subquery

### 1045. Customers Who Bought All Products
Write a solution to report the customer ids from the Customer table that bought all the products in the Product table. \
Return the result table in any order.
- Solution Hint : Subquery

### 1731. The Number of Employees Which Report to Each Employee
For this problem, we will consider a manager an employee who has at least 1 other employee reporting to them. \
Write a solution to report the ids and the names of all managers, the number of employees who report directly to them, and the average age of the reports rounded to the nearest integer. \
Return the result table ordered by employee_id.
- Solution Hint : GROUP BY / JOIN

### 1789. Primary Department for Each Employee
Employees can belong to multiple departments. When the employee joins other departments, they need to decide which department is their primary department. Note that when an employee belongs to only one department, their primary column is 'N'. \
Write a solution to report all the employees with their primary department. For employees who belong to one department, report their only department.
- Solution Hint : GROUP BY / UNION / ORDER BY

### 610. Triangle Judgement
Report for every three line segments whether they can form a triangle. \
Return the result table in any order.
- Solution Hint : Triangle inequality x + y > z and x + z > y and y + z > x , CASE

### 180. Consecutive Numbers
Find all numbers that appear at least three times consecutively. \
Return the result table in any order.
- Solution Hint : FROM multiple tables

### 1164. Product Price at a Given Date
Write a solution to find the prices of all products on 2019-08-16. Assume the price of all products before any change is 10. \
Return the result table in any order.
- Solution Hint : CTE / JOIN / UNION

### 1204. Last Person to Fit in the Bus
There is a queue of people waiting to board a bus. However, the bus has a weight limit of 1000 kilograms, so there may be some people who cannot board. \
Write a solution to find the person_name of the last person that can fit on the bus without exceeding the weight limit. The test cases are generated such that the first person does not exceed the weight limit.
- Solution Hint : CTE / Window function

### 1907. Count Salary Categories
Write a solution to calculate the number of bank accounts for each salary category. The salary categories are:

- "Low Salary": All the salaries strictly less than $20000.
- "Average Salary": All the salaries in the inclusive range [$20000, $50000].
- "High Salary": All the salaries strictly greater than $50000.
  
The result table must contain all three categories. If there are no accounts in a category, return 0. \
Return the result table in any order.
- Solution Hint : UNION

### 1978. Employees Whose Manager Left the Company
Find the IDs of the employees whose salary is strictly less than $30000 and whose manager left the company. When a manager leaves the company, their information is deleted from the Employees table, but the reports still have their manager_id set to the manager that left. \
Return the result table ordered by employee_id.
- Solution Hint : Subquery

### 626. Exchange Seats
Write a solution to swap the seat id of every two consecutive students. If the number of students is odd, the id of the last student is not swapped. \
Return the result table ordered by id in ascending order.
- Solution Hint : CASE / ORDER BY

### 1341. Movie Rating
Write a solution to:
- Find the name of the user who has rated the greatest number of movies. In case of a tie, return the lexicographically smaller user name.
- Find the movie name with the highest average rating in February 2020. In case of a tie, return the lexicographically smaller movie name.

- Solution Hint : UNION

### 1321. Restaurant Growth
You are the restaurant owner and you want to analyze a possible expansion (there will be at least one customer every day). \
Compute the moving average of how much the customer paid in a seven days window (i.e., current day + 6 days before). average_amount should be rounded to two decimal places. \
Return the result table ordered by visited_on in ascending order.
- Solution Hint : Subquery / GROUP BY

### 602. Friend Requests II: Who Has the Most Friends
Write a solution to find the people who have the most friends and the most friends number. \
The test cases are generated so that only one person has the most friends.
- Solution Hint : UNION ALL / CTEs

### 585. Investments in 2016
Write a solution to report the sum of all total investment values in 2016 tiv_2016, for all policyholders who:
- have the same tiv_2015 value as one or more other policyholders, and
- are not located in the same city as any other policyholder (i.e., the (lat, lon) attribute pairs must be unique).
- 
Round tiv_2016 to two decimal places.
- Solution Hint : Subquery

### 185. Department Top Three Salaries
A company's executives are interested in seeing who earns the most money in each of the company's departments. A high earner in a department is an employee who has a salary in the top three unique salaries for that department. \
Write a solution to find the employees who are high earners in each of the departments. \
Return the result table in any order.
- Solution Hint : Subquery / CTEs

### 1667. Fix Names in a Table
Write a solution to fix the names so that only the first character is uppercase and the rest are lowercase. \
Return the result table ordered by user_id.
- Solution Hint : string functions

### 196. Delete Duplicate Emails
Write a solution to delete all duplicate emails, keeping only one unique email with the smallest id.
For SQL users, please note that you are supposed to write a DELETE statement and not a SELECT one.
For Pandas users, please note that you are supposed to modify Person in place.
After running your script, the answer shown is the Person table. The driver will first compile and run your piece of code and then show the Person table. The final order of the Person table does not matter.
- Solution Hint : DELETE

### 176. Second Highest Salary
Write a solution to find the second highest salary from the Employee table. If there is no second highest salary, return null (return None in Pandas).
- Solution Hint : Subquery

### 1484. Group Sold Products By The Date
Write a solution to find for each date the number of different products sold and their names. \
The sold products names for each date should be sorted lexicographically. \
Return the result table ordered by sell_date.
- Solution Hint : GROUP BY / ORDER BY

### 1327. List the Products Ordered in a Period
Write a solution to get the names of products that have at least 100 units ordered in February 2020 and their amount. \
Return the result table in any order.
- Solution Hint : GROUP BY / INNER JOIN

### 1517. Find Users With Valid E-Mails
Write a solution to find the users who have valid emails. \
A valid e-mail has a prefix name and a domain where:

- The prefix name is a string that may contain letters (upper or lower case), digits, underscore '_', period '.', and/or dash '-'. The prefix name must start with a letter.
- The domain is '@leetcode.com'.

Return the result table in any order.
- Solution Hint : REGEX
