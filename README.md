# Seating-Arrangement-Optimization

Utilizing puLP and Gurobi python frameworks to optimize a seating arrangement for a Conference

This takes a dataset of Random Names and attributes as an input and creates an optimized seating schedule for multiple sessions and multiple tables in each session. 



## Mathematical Programming Model Aspects: 
Constraints: 
1. Each pair of attendees may not be seated at the same table more than 3 times throughout all sessions
2. 

Optimization Goals: ** CHANGE THESE TO NOT BE AS SIMILAR TO THE ACTUAL THING**
1. Group A preferences for members of group B
2. Group B preferences for members of group A 
3. Matching on AUM Class 
4. Matching on ...


Decision Variables: 
1. seated_vars:
    - one variable for each person at each table in each session
    - Binary, taking on value of 0 (not seated at this table in this session) or 1 (seated at this table in this session)

2. table_pair_session_vars: 
    - one variable per pair per session
    - Binary, taking on value of 0 (not seated together in this session) or 1 (seated together in this session)

3. 

