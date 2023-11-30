Overview:
Introduction: This project walks through the process of sorting query results and joining tables in SQL. It covers essential concepts for basic SQL querying.

Tools Used: SQLiteStudio.

Content Breakdown:
Introduction to Sorting: The project begins by explaining the usage of the ORDER BY clause to modify the order of displayed rows in query results.

Joining Tables: The project progresses to illustrate the syntax required for retrieving data from two tables using the JOIN command in SQL.

Demonstration and Exploration: Screenshot: A database schema screenshot showcasing the 'orders' and 'customers' tables with relevant columns is included.
Data Analysis: Discusses the significance of using correct syntax and the benefits of efficiently retrieving data via SQL queries.

Code Structure and Best Practices:
Indentation: Emphasizes code readability through indentation practices, specifically within SQL queries.
Explanation: Highlights the importance of accurate syntax in executing successful SQL queries and ensuring desired output.

![Image](https://github.com/users/newtongeorges/projects/2/assets/98448503/b9780eab-c865-48ef-a1dc-4e8718fae4d9)
Every retrieval begins with the SELECT list(one, many, or all of the fields from the table)
Retrieving the name of the table where the data resides is accomplished using a FROM clause
In most RDBS, a semicolon ends the query
Execute/run query to retrieve table

![Image](https://github.com/users/newtongeorges/projects/2/assets/98448503/b2f527e0-709a-4ab7-9334-5d5b677423f1)
The status line displays an ERROR message if you input incorrect data
ERROR: no such column: cust
Make corrections accordingly and re-run query

![Image](https://github.com/users/newtongeorges/projects/2/assets/98448503/1c41c5a2-9144-47cb-b758-8b15ca02dd32)
WHERE clause follows the FROM clause
Condition begins with a field whose value is being tested, then a comparison operator, and finally a data value(# or '')

![Image](https://github.com/users/newtongeorges/projects/2/assets/98448503/f4895258-dfed-4892-822b-6588d4ef8e2a)
Compound WHERE clause Syntax(and, or, not)
The filter is testing more than one condition

![Image](https://github.com/users/newtongeorges/projects/2/assets/98448503/ad11c508-b1ff-4131-9caa-ac20fbd6e732)
All of the data in the respectively table can be viewed independently

![Image](https://github.com/users/newtongeorges/projects/2/assets/98448503/f78cf2bd-d7ec-4ba9-a47d-1112e256b585)
Many times the order in which the row display needs to be modified using ORDER BY
The ORDER BY clause comes after the WHERE clause


![Image](https://github.com/users/newtongeorges/projects/2/assets/98448503/f5b308d2-8035-4bdb-ba7a-d714588c8d30)
Syntax required for retrieving data from two tables in one query: JOIN command
When joining two tables the from clause must include the names of both tables
The ON clause is added to the join code to provide SQL with the names of the columns that have common data between the two tables.

Project Conclusion: Summarizes the importance of understanding SQL syntax, ensuring query accuracy, and applying best practices.
