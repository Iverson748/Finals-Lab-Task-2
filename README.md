## Transforming ER Model to Relational Tables
In converting the ER diagram, the following are the data types of the attributes:
## Student Table:
username: String (VARCHAR), up to 50 characters.
##  Assignment Table:
shortname: String (VARCHAR), up to 50 characters.
due\_date: Date, cannot be null.
url: String (VARCHAR), up to 255 characters, can be null.
## Submission Table:
username: String (VARCHAR), up to 50 characters.
shortname: String (VARCHAR), up to 50 characters.
version: Integer, represents the version of the submission.
submit\_date: Date, cannot be null.
data: Text.
## Note: Create the appropriate table relationship and enforce necessary REFERENTIAL INTEGRITY CONSTRAINTS
## Query Statements
