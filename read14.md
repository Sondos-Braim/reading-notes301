# Read 14

## DATABASE NORMALIZATION

-Database normalization is a process used to organize a database into tables and columns.  The main idea with this is that a table should be about a specific topic and only supporting topics included.

-By limiting a table to one purpose you reduce the number of duplicate data contained within your database. This eliminates some issues stemming from database modifications.

-There are three main reasons to normalize a database.  The first is to minimize duplicate data, the second is to minimize or avoid data modification issues, and the third is to simplify queries.

-There are three modification anomalies that can occur:

-`Insert Anomaly`

-There are facts we cannot record until we know information for the entire row.  In our example we cannot record a new sales office until we also know the sales person.  Why?  Because in order to create the record, we need provide a primary key.  

-`Update Anomaly`

-In this case we have the same information in several rows. For instance if the office number changes, then there are multiple updates that need to be made.  If we don’t update all rows, then inconsistencies appear.

-`Deletion Anomaly`

-Deletion of a row causes removal of more than one set of facts.  For instance, if John Hunt retires, then deleting that row cause us to lose information about the New York office.

-Normalization makes it easier to search and sort your data.

-First Normal Form – The information is stored in a relational table with each column containing atomic values. There are no repeating groups of columns.

-Second Normal Form – The table is in first normal form and all the columns depend on the table’s primary key.

-Third Normal Form – the table is in second normal form and all of its columns are not transitively dependent on the primary key.
