#Week 13: Overview #

## Cloud Computing ##

This week we will build on the cloud computing introduction provided in Week 12 to introduce the map-reduce paradigm, which extends the functional programming constructs we discussed earlier in this course to large data by using the Hadoop infrastructure. Next, we introduce NoSQL data stores, which are generally recent
additions to the database world that provide functionality beyond that
provided by traditional relational databases, often to enable fast
processing of very large data sets. Typically these systems differ from
a relational database by violating a specific item in the relational
database _ACID_ test. Often this is consistency, which means that a
select query might return different results depending on when it is run.
This might be important for a shopping cart application for an online
retailer, for example, who might be more interested in fast responses to
user requests than an exact count of the number of items remaining in
the inventory. This week, we specifically focus on document oriented data stores like MongoDB.

### Objectives ###

#####By the end of this lesson, you should be able to:######

- Understand the MapReduce approach to computing
- Be able to execute MapReduce tasks in a Hadoop environment. 
- Understand the basic concepts of a NoSQL database.
- Understand the basics of documented-oriented databases
- Understand how to connect to these database from a Python program.
- Be able to insert, update, select, and delete data from these database
by using a Python program.

### Activities and Assignments ###

|Activities and Assignments | Time Estimate | Deadline* | 
|:------| -----|---------:|
|**[Week 13 Lesson 1: Introduction to Map/Reduce](lesson1.md)**| 3 Hours | Monday|
|**[Week 13 Lesson 2: Introduction to Document Databases (NoSQL)](lesson2.md)**| 3 Hours |Wednesday|

*Please note that unless otherwise noted, the due time is 6pm Central time!*

----------