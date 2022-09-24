# Relational and Non-Relational Databases in the context of Data Engineering

 A Database is an organized collection of large volumes of data, typically stored electronically in a computer system. A database is usually controlled by a database management system (DBA), which is used to store and retrieve data orderly. 
 
 In order for a database to be reliable, it needs four important properties that form the acronym ACID: atomicity, consistency, isolation, and durability.
 
* Atomicity means that all changes on data are either performed or not performed, as if they were a single operation;
* Consistency secures that a database is stable before and after any transaction;
* Isolation ensures that multiple transactions executing at the same time do not affect one another’s execution. As a result, they appear to be sterilized.
* Durability ensures that, once a transaction is completed, it won’t be undone.

 There are many different types of databases. In this article, I draw attention to the two leading ones: relational and non-relational databases.
 
A relational database (RDB) is used to store data in sets of tables, rows, and columns. An RDB is capable of establishing links, or relationships, between information by joining tables, which makes it easy to understand and gain insights about the connections between various data points. Mostly all relational databases use Structured Query Language (SQL) to access and manipulate the data stored in the database. 
 
An advantage of the relational database model is that it provides an intuitive way to represent data and allows access to related data points. Other advantages include ACID compliance, since it ensures data validity regardless of errors, failures, or other potential mishaps. It is flexible and easy to use. One can easily add, update, or delete tables, relationships, and make other changes whenever needed without affecting the overall structure or impacting existing applications.

This method of storing information in tables and creating a relationship between them may have some drawbacks. For instance, it can give rise to high complexity if data can not be easily encapsulated in a table. Also, once the amount of data turns massive, the database has to be partitioned across multiple servers, which can cause several problems because joining tables that have been distributed in distinct servers is not an easy task.

Non-relational databases were created in order to provide a response to these limitations. The main difference between relational and non-relational databases relies on how data is stored and organized. The last, also called NoSQL (non SQL, or sometimes, Not Only SQL), does not use relations as its storage structure. Instead, they store data as individual, unconnected files and can be used for complex, unstructured types, such as documents, or rich media files.

Some advantages of the NoSQL model are the high scalability and high availability. It is capable of handling large volumes of tada at high speed with a scale-out architecture. It means that scalability is reached by spreading the storage of data and the work to process the data over a large cluster of computers. In order to increase capacity, more computers are added to the cluster. This type of architecture is not difficult to implement in cloud computing environments where new computers and storage can be easily added to the cluster. Achieving the same type of scalability with SQL databases is possible. However, it can be expensive since it requires lots of engineering. 

The NoSQL model also has its drawbacks. Not all of the models abide by ACID properties. Therefore, developers have to tie things together with programming to apply ACID restraints, which are provided in relational databases. Additionally, most of them are open source software, which causes them to compromise in reliability as nobody is responsible in times of failure.

As described, both models have advantages and disadvantages in different situations, making it hard to say which one is better. It is important for the programmer to analyze the project that needs to be developed and compare the pros and cons of each model and then decide which one to use. 
  
  
  

Reference list

GOOGLE CLOUD. What is a relational database? Retrieved from: https://cloud.google.com/learn/what-is-a-relational-database#:~:text=A%20relational%20database%20is%20a,structures%20relate%20to%20each%20other.

IBM. ACID properties of transactions. Retrieved from: 
https://www.ibm.com/docs/en/cics-ts/5.4?topic=processing-acid-properties-transactions

JATANA, Nishtha et al. A survey and comparison of relational and non-relational database. International Journal of Engineering Research & Technology, v. 1, n. 6, p. 1-5, 2012.

MONGODB. Advantages of NoSQL Databases. Retrieved from: https://www.mongodb.com/nosql-explained/advantages

ORACLE. What is a Relational Database (RDBMS)? Retrieved from: https://www.oracle.com/database/what-is-database/


