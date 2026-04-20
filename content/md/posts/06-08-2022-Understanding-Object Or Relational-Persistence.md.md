{:title  "Understanding Object/Relational Persistence"
 :layout :post
 :date   "2022-08-06"
 :tags   ["Java" "Hibernate"]
 :author "Shubham Setia"}


I have started reading Java Persistence with Hibernate. With the series of blog posts, I will try to capture things that I have learned. So let's get started. In this post, I will cover:
- What is Object Persistence
- Basic SQL terminologies
- Using SQL in Java
- Object/Relational Paradigm Mismatch
- Basic Introduction to ORM and JPA

## What is object persistence?
Almost all application needs persistent data. Persistence is one of the fundamental concept in application development. If an information system didn't preserve data, it would loose data when it was powered off.

Object persistence means individual object can outlive the application process; they can be saved to a data store and be re-created at later point in time. When we talk about persistence in Java, we're normally talking mapping and sotring object instances in databse using SQL.