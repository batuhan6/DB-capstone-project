# Database Engineer Capstone Project

In this project, I created a data model for a Restaurant and deploy it in the MySQL database. This includes a set of tables to store relevant information. I have populated the tables with some records of data for testing purposes. In addition, I have analyzed data using the restaurants Excel Data File. Further, I have completed the data analysis in Tableau.

An ER Diagram has been created and implemented in MySQL Workbench using the forward engineering method.

Sales report is created from the Database. A booking system is build and data insights is generated.

Created these sales reports using queries, procedures and prepared statements

Queries 
- VIRTUAL TABLES:To make use of data that exist in other tables and to simplify data access inquiries.
- JOINS:Link records of data between one or more tables based on a common column. 

Stored Procedures 
- Reusable code that can be invoked and executed efficiently. 

Prepared Statements 
- MySQL compiles and parses just ones, and then knows it's safe to execute.(Prepared statements are a much more efficient and optimal way of executing statements without using valuable MySQL resources.) 

<!-- Another task you assisted Little Lemon with involved building a table booking system in their database that they could use to keep track of guests visiting the restaurant. This task mainly consisted of using SQL queries and transactions. -->

Created a booking system. User can track the bookings. This task mainly consisted of using SQL queries and transactions. I used some examples of the SQL queries and transactions. Data is created, updated and deleted. Data is being read using read queries like select statements. I also made use of triggers to store a set of actions in the form of a stored program that could then invoke automatically when certain events occurred.

Tableau, the data visualization tool. The process steps that being followed, to complete this task, I first connected to data sources to Tableau. Then I prepared the data for analysis and focused on the most relevant data. The next step was to create a visualization of the data using its Ui elements. Finally Tableau is being used, to produce interactive real time data visualizations in the form of dashboards. These process steps, helped to provide clear and relevant answers, to booking systems important business questions. 

A database client is being created so that the owner could interact with their database using a python base application. 


I have used the following tools and software for this project:

* Git,
* MySQL Workbench,
* Tableau,
* Python,
* Jupyter Notebook,

In this project, I have proven my ability to:

* Set up a database project,
* Create a sales reports,
* Create a booking system,
* Work with data analytics and visualization,
* Create a database client.

<pre>
  I start the project by creating Workbench diagram
</pre>

![1](https://github.com/batuhan6/DB-capstone-project/assets/32600613/9e71dd02-08eb-4d31-9dd3-1e318a09203c)

Views is written for course names.
![views_coursesnames](https://github.com/batuhan6/DB-capstone-project/assets/32600613/e3612ca2-03c2-4850-9a31-8999bfd62d19)


Trigger that creates autoomatically create date when new booking created. 
![1](https://github.com/batuhan6/DB-capstone-project/assets/32600613/f642bea4-58b3-4148-b4b6-9f038838b29b)

Add booking procedure.
![2](https://github.com/batuhan6/DB-capstone-project/assets/32600613/ebf2acda-9613-4367-b430-4ac0ef1413fd)

Update booking procedure
![3](https://github.com/batuhan6/DB-capstone-project/assets/32600613/34ad8d9d-384e-4a54-a6a1-16c6958d24f1)

Cancel booking procedure
![4](https://github.com/batuhan6/DB-capstone-project/assets/32600613/66bc135e-c565-4579-9bd4-fdc8f77285a5)

GetMaxQuantity procedure
![5](https://github.com/batuhan6/DB-capstone-project/assets/32600613/0aa45dae-6017-4cc9-b6ce-ca69dfa17eb1)

Manage booking procedure
![7](https://github.com/batuhan6/DB-capstone-project/assets/32600613/9de38eea-434f-4dd3-9579-e39a8f706b88)

Join operations. Queries that gives the number of bookings per cities and the number of orders per cities.
![8](https://github.com/batuhan6/DB-capstone-project/assets/32600613/1e8ed361-6db7-4a12-8511-25f0b3891095)




In this heatmap we see the distribution of main course orders in year 2023.
![3](https://github.com/batuhan6/DB-capstone-project/assets/32600613/a9113895-3dc4-4183-956a-dfd71d412325)

This graph shows us the number of main course orders per country in year 2023 
![2](https://github.com/batuhan6/DB-capstone-project/assets/32600613/9a25f5f0-afe5-47d4-894b-9746bd1a591c)

This graph shows us the distribution of number of drinks ordered in year 2023.
![4](https://github.com/batuhan6/DB-capstone-project/assets/32600613/a36784fa-4f97-41e1-b658-53965fd605c8)

