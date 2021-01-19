# Normal Form

Objectives of Normal From
- free the database from unwanted insertions, updates, & deletion dependencies
- reduce need to refactor database
- make database neutral to query stats
- make relational model more informative

- How to reach First Normal Form (1NF):
  - Atomic values: each cell contains unique and single values
  - Be able to add data without altering tables
  - Separate different relations into different tables
  - Keep relationships between tables together with foreign keys

- Second Normal Form (2NF):
  - Have reached 1NF
  - All columns in the table must rely on the Primary Key

- Third Normal Form (3NF):
  - Must be in 2nd Normal Form
  - No transitive dependencies
  - Remember, transitive dependencies you are trying to maintain is that to get from A-> C, you want to avoid going through B.
  - Most that should be sought after in practice
