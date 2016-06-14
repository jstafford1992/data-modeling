# data-modeling

Standard
- Design and implement schemas
Objectives
- Model database schemas using ERDs
- Diagram cardinality using a Crow's foot

## Database examples:

* tournament site
  * teams
  * player
  * games
  * tournaments
* sticker
  * stickers
  * users
  * categories
* music venue
  * members
  * musicians
  * bands
  * events
* weather research facility
  * tempeatures
  * locations

## NOTES:

  * entities contain table name column names
  * entity relations (the cardinality of the table)
    * one-to-one
    * one-to-many
    * many-to-many
    * one-and-only-one-to-many
    * zero-or-one


# Modeling: Part II
​

## Review 
​
* What is a database schema? 
* Does a database schema contain data?
* Does a table have a specified number of columns?
* Does a table have a specified number of rows?
* What is a record in a table?
* What is a field in a table?
* What is a primary key?
* What is a foreign key?
* What is a natural key (AKA business key)?
* Can you use a primary key as a foreign key for another table?
* Name 5 data types?
​

## Composite Key
​
* Refers to cases where more than one column is used to specify the primary key of a table. In such cases, all foreign keys will also need to include all the columns in the composite key. Note that the columns that make up a composite key can be of different data types.
​

## Review ERDs
​
* What is an ERD?
	* logical representation of a schema
	* represents tables, fields, types and relationships
​

## Notation Review
​
* one-to-one
* one-to-many
* one-or-more
* one-and-only-one
* zero-or-one
* zero-or-many
​
* This is "Information Engineering Style
* Other styles: Chen and Bachman
	

## Galvanize Demo
​
* Instructors and cohorts
* Lookup table for instructor type
* Many-to-many problem - join table
* Why not join students directly to instructors? WHy are many-to-many relationships bad?
​

## Join Tables (AKA Associative Tables)
​
* Help resolve a many-to-many relationship
* Naming convention - combine in alphabetical order
​

## Lookup Tables
​
* A lookup table helps you create options or precalculated info
​

## Exercise: Actors and Films (with lookup and join tables)
​
​
## Extra Practice
Choose a scenario with data and create an ERD.
​
* Airlines, planes, and flights
* The library, books, check outs
* Foods, ingredients, nutrition
* Employees, positions, salaries, bosses
* Computers, components, price, specs
* Crime, location, severity, victim
* Houses, location, price, sqft, days on market
* Symptoms, age, smoker, drinker, gender, disease or ailment
