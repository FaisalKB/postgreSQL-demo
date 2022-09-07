# postgreSQL Demo

## A demonstration of rudimentary postgreSQL database management.

Databases are incredibly prevalent. They underlie the technology that you use every day—or even every hour!

Databases reside behind a huge percentage of websites. They're a crucial component of e-commerce systems, telecommunications systems, banking systems, video games, and just about any other software system or electronic device that maintains some amount of persistent information. They're also reliable, efficient, and scalable, and these properties make them exceptionally useful and convenient.

Databases are so ubiquitous and important that every company has at least one database to store company information such as employee records, credit and payment records, salary details, and more.

## What is a database?

A database is defined as an organized collection of data, generally stored and accessed electronically from a computer system.

Companies rely heavily on databases to store the data that powers their applications. Databases store a variety of data, such as usernames, email addresses, and nearly every other type of information that you can imagine.

## Why use databases?

Imagine that you are opening an online store to sell handmade treats to pet owners. You would want to keep track of all sorts of information about your sales. Most people would open a spreadsheet and start inputting information as the orders come in.

Suppose that you have a customer, Mary, who buys a box of Bacon Bark Sticks. You capture all of that order information. Then, as you receive more orders, you record the same information for each customer. Later, Mary buys something else: a dozen Cheesy Dog Biscuits. But now, she's moved to a bigger home to have more room for all of her pets, so her address is different. Now you have Mary's name duplicated, and you have contradicting values for her address. If your handmade treats store becomes enormously popular, these issues will escalate.

A few months later, Mary calls to ask about one of her orders. When you pull up the orders with her name, you see three different addresses.You can't be sure whether each of these orders belongs to the person calling, because there is nothing uniquely identifying the three different Marys. As you can see, this might lead to a messy situation. Customers might get mixed up, or the wrong products could be sent to a customer.

How would you resolve this? Instead of having one massive spreadsheet, you can use a database and separate the information into separate bite-size "spreadsheets" called tables, which are a collection of related data held in a table format within a database.

## Database management tools and concepts demonstrated in this repository:

### Structured Query Language (SQL)

Structured Query Language (SQL) is the database language used to perform operations on a database. You can also use SQL to create a database. SQL uses certain commands, such as ```CREATE```, ```DROP```, and ```INSERT```, to carry out various tasks.

SQL operations can be performed on any object in the database, not just tables. But to simplify things, this lesson will focus on SQL commands operating on tables only.

SQL commands fall into four categories:

- Data definition language (DDL)

- Data query language (DQL)

- Data manipulation language (DML)

- Data control language (DCL)

This demonstration will showcase DDL, DQL and DML. DCL, which is used by database administrators to configure security access to the database, is out of scope for this repository.


### Data definition language (DDL)
Data definition language (DDL) is a subset of SQL commands that is used to define the tables in the database. It is used to create and modify any object in the database, but this demonstration showcases using it to create and modify the tables; creating by using ```CREATE``` .

### Data manipulation language (DML)
Now that a table exists in the database, you can insert rows of data into the table. DML, a subset of SQL commands used to manipulate data in the database. If you want to create data, you need to use the SQL keyword ```INSERT```.

### Data query language (DQL)
Now that some data exists in the database, you need a way to retrieve that data. One of the most important aspects of using a database is the practice of retrieving data, whether it's on an ad hoc basis or part of a process that's been coded into an application. There are several ways to retrieve information from a database, but one of the most commonly used methods is submitting queries. A query is any command used to retrieve data from a table. In SQL, queries are almost always made using the ```SELECT``` statement.

### Updating/Deleting Data
Eventually, we learn that the only constant in software is change. We can be sure that, over time, the data in the database will have to be changed or removed. If you want to change or remove data in the database, you need to use the SQL keywords ```UPDATE``` and ```DELETE```.

