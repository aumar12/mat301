
## Problem Set 3 

1. Define the terms: relation, tuple, attribute, record, and field.
Relation is a table; a set of tuples, not ordered list. Relations change over time (tables get updated). Tuples are rows of a relation. Tuples have one component for each attribute. Attributes are columns of tables. Record (a.k.a. row) of a relation (table).

2. What are keys in a relation?
Keys play an important part in relational models (thus database design). Keys are one or more attribute in a relation used to identify a record. Keys ideally are unique, however, it is possible to have a nonunique key.

3. What is a surrogate key and how is it used?
Surrogate key is a column made by an arbitrary assignment of a key to a row. Mostly, a surrogate key is an auto-incremented integer that has no connection to the data and is void of meaning. For example, a __natural key_for products is the UPC since it is unique to each product and each product has (or should have) a UPC. Though the UPC can become obselete that is why a generic surrogate key is a better choice.

4. In the following equation, Area = Length x Width, identify the determinant(s).
Length and Width are determinants.

5. If a relation has no duplicate data, how can you be sure there is always at least one primary key?


6. Give an example of a relation.  Determine a natural key for this relation.

  For question 7 - 8, Consider product *orders*.  In particular, associated with an order is: customer name (first and last), address (street, city, state, zip), phone, email, the products orders (including item, quantity, and price).  

7. Create a relational data model for *orders*.  Consider applying normalization rules (discuss Monday)

8. For customer, could email be used as a primary key?  If so, state why.  Also, if possible to use as a primary key, discuss any disadvantages of using email as a primary key.

9. Given two relations S and R below find the Cartsian Product S x R. 
1 2 3 1 1 
1 2 2 2 3
1 2 2 1 5
2 3 3 1 1
2 3 2 2 3
2 3 2 1 5

10. Find the natural join between the Faculty and Department relations below.

S
--------------
| A | B |
|---|---|
| 1 | 2 |
| 2 | 3 |
---------

R
------------
| C | D | E |
|---|---|---|
| 3 | 1 | 1 |
| 2 | 2 | 3 |
| 2 | 1 | 5 |



Faculty
--------------
| Name | ID | Dept |
|-------|----|----------------|
| Joe | 1 | Chemistry |
| Susan | 2 | Math |
| Tom | 3 | Marine Science |
| Mike | 4 | Math |


Department
------------
| Dept | Chair  |
|---|---|
| Chemistry | John |
| Math | Mike |
| Marine Science | Barry |
