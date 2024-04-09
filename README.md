# goit-rdb-hw-05

Master's degree. Relational databases: Nested requests | Code reuse

1. Write an SQL query that displays the order_details table and the customer_id field from the orders table respectively for each record in the order_details table. This should be done using a nested query in the SELECT statement.

2. Write an SQL query that displays the order_details table. Filter the results to ensure that the corresponding record from the orders table satisfies the condition shipper_id=3. This should be done using a nested query in the WHERE clause.

3. Write an SQL query, nested in the FROM clause, that selects rows with the condition quantity>10 from the order_details table. For the obtained data, find the average value of the quantity field — group by order_id.

4. Solve task 3 using the WITH operator to create a temporary table temp. If your MySQL version is earlier than 8.0, create this query by analogy to how it is done in the notes.

5. Create a function with two parameters that will divide the first parameter by the second. Both parameters and the returned value should have the FLOAT type. Use the DROP FUNCTION IF EXISTS construct. Apply the function to the quantity attribute of the order_details table.
