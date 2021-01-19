# When to Not Use NoSQL Database

- Need ACID transactions
- Need to do JOINS
  - this will result in a full db scan which is bad
- need aggregations or analytics
- changing business requirements
- small data
