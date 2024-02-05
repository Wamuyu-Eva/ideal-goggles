## Introduction

Column A depends on column B means each B value is related to at most one A value.
Columns A and B may be simple or composite.
'A depends on B' is denoted B → A. Dependence of one column on another is called functional dependence.

Redundancy occurs when a column depends on another column that is not unique.

In a Boyce-Codd normal form table, all dependencies are on unique columns.
Dependence on a unique column never creates redundancy, so Boyce-Codd normal form eliminates all redundancy arising from functional dependence.

## Third normal form

Informally, a table is in third normal form when all non-key columns depend on the key, the whole key, and nothing but the key.
This definition is accurate when the primary key is the only unique column.

A candidate key is a simple or composite column that is unique and minimal. Minimal means all columns are necessary for uniqueness. A table may have several candidate keys. The database designer designates one candidate key as the primary key.

A non-key column is a column that is not contained in a candidate key.

A table is in third normal form if, whenever a non-key column A depends on column B, then B is unique. Columns A and B may be simple or composite. Although B is unique, B is not necessarily minimal and therefore is not necessarily a candidate key.

## Boyce-Codd normal form

The definition of third normal form applies to non-key columns only, which allows for occasional redundancy. Boyce-Codd normal form applies to all columns and eliminates this redundancy.

A table is in Boyce-Codd normal form if, whenever column A depends on column B, then B is unique. Columns A and B may be simple or composite. This definition is identical to the definition of third normal form with the term 'non-key' removed.

Boyce-Codd normal form is considered the gold standard of table design. Although fourth and fifth normal forms remove additional types of redundancy, these redundancies are uncommon and of little practical concern.

***Trivial dependencies***

Trivial dependencies is when the columns of A are a subset of the columns of B. A always depends on B. 

## Applying Normal Form

Normalization eliminates redundancy by decomposing a table into two or more tables in higher normal form. Ex: A table in first normal form might be replaced by two tables in third normal form. 
In principle, normalization decomposes tables to any higher normal form. Fourth and fifth normal form are complex, however, and have limited practical value. As a practical matter, database designers usually normalize tables to Boyce-Codd normal form.

Column A depends on column B when each B value is related to at most one A value. A and B may be simple or composite columns. In a Boyce-Codd normal form table, if column A depends on column B, then B must be unique. Normalizing a table to Boyce-Codd normal form involves three steps:

***List all unique columns***. Unique columns may be simple or composite. In composite columns, remove any columns that are not necessary for uniqueness. The primary key is unique and therefore always on this list.

***Identify dependencies on non-unique columns***. Non-unique columns are either external to all unique columns or contained within a composite unique column.

***Eliminate dependencies on non-unique columns***. If column A depends on a non-unique column B, A is removed from the original table. A new table is created containing A and B. B is a primary key in the new table and a foreign key in the original table.

Normalization eliminates redundancy by removing A from the original table. Since the data relating A and B is recorded in a new table, no information is lost.


## Denormalization
