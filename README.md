Combining data from two or more zero-trust knowledge databases where data access is restricted.
Introduction
In many organizations, multiple databases may be used to store disparate, but connected data. For example, a holiday company may have a database of holiday destinations and a separate database of customers. However, customer and destination data may be connected. For example, customers may visit (or may have visited) one or more of the destinations.
Problem Statement
Some use cases require retrieval of data from disparate databases. This is complicated when users are restricted (on a zero-trust basis) in the data (or type thereof) they can access from these databases.
Objectives
Develop the methodology and practically demonstrate the combination of data from two databases (particularly graph databases) where users are restricted in the category of data they may access. Each graph database should have a separate zero-trust access. Individual data points should be labeled with an access level 1 or 2 (over both databases). Individual users may be granted a level of access: Level 1 users can access level 1 data; level 2 users can access both level 1 and level 2 data.
