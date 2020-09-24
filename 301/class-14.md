
## Database Normalization

- database normalization is a process used to organize a database into tables and columns
- main idea is that the table sould be on a specific topic and supporting topics
- three main reasons for nomalizing a database:
  - the first is to minimize duplicate data 
  - the second is to minimize or avoid data modification issues
  - the third is to simplify queries. 

#### three rules for database normalization that upon each other:

- First Normal Form – The information is stored in a relational table with each column containing atomic values. There are no repeating groups of columns.
- Second Normal Form – The table is in first normal form and all the columns depend on the table’s primary key.
- Third Normal Form – the table is in second normal form and all of its columns are not transitively dependent on the primary key

[<== Back to Main Readme](README.md)