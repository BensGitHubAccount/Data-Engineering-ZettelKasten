# Structuring a Database

- Normalization: reduce redundancy and increase integrity
- Denormalization: must be done in read heavy workloads to increase performance
  
Fact vs Dim tables
- Fact contains data and Dim contains pointers to the tables with info

Star & Snowflake
- The star pattern is a subset of the snowflake pattern
- uses fact tables to point to dim tables in hub/spoke pattern
