# NoSQL Research Lab

## Explainer
Up until now in the cohort we have stored data only in what are known as relational databases (SQL is the most well known type of relational DB querying language). Relational databases structure our data into tables. Today we will learn about a different type of database: a non-relational one. 

## Lab

In this lab you will be researching, either individually or in groups, answer to the following questions about noSQL databases. The intention is for you to spend some time learning about the fundamental differences between the type of databases we have seen before and the new type we will be learning about today. Even more importantly, you will learn about why two types of databases are used, and what situations fit each type of db. 

## Setup

Fork and clone this repository and answer questions as you research directly in the README. You do not have to submit this lab, but you will want to have it on hand for reference in the future. 

# Questions:
1. What does the term noSQL refer to, and what other term is often used synonymously with noSQL?
2. What are some of the common arguments for using a non-relational versus a relational db?
3. In this class we will be using the document style of non-relational databases. What are the charecteristics of a document based db? 
4. In this class we will be using Mongo specificially as our no-SQL db. Look into Mongo and answer this question: what is the priamry difference between how Mongo is maintained vrs SQL?
5. Mongo DBs are organized into documents. Describe an example of a table in SQL that contains users, and then describe the equivalent DB setup in Mongo. 
6. What is an example situation where a Mongo database makes sense versus a non-relational db?



1. - Nosql means non tabular and store data differently than relational tables, also known as non relational database. many say that relational data in noSQL databases are is easier because related data doesnt have to be split between tables

2 - flexible data models, horizontal scaling, fast queries, easy for developers:
      flexible data models - very flexible schemas allowing to make changes easily
      horizontal scaling - you can add cheaper commodity servers when necessary unlike SQL's vertical scaling which more expensive
      fast queries - NoSQL databases are optimized for queries, does not require joins | Data that is accessed together should be stored    together
      easy for developers - NoSQL databases such as MongoDB stores its data structures in the same way that developers store their data in an application
      
3 - databases uses file types that are natural and flexible with developers to work with such as a JSON. No need to decompose data across tables, less code to write and users get higher performance
  Allows querying data to be comprehensive and expressive
  document databases are distributed systems
  
4 same as 2

5 in SQL, you have to join users to other data tables to establish a relation whereas for MongoDB, data that is accessed together is stored together meaning its not required to join other tables to establish a relation

6 an example would be a social media app where users have a lot of custom content / an example of an ORM would be data used in different departments of a company 
