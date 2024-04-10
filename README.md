Exercise 2: Subquery with Conditional Filtering

Objective: Practice using subqueries with conditional filtering.

Scenario:In your database, you have a table named **orders** containing information about orders placed by customers. You also have a table named **customers** containing information about customers.

1.  **orders** table:
    
    *   Columns: order\_id (integer), customer\_id (integer), total\_amount (numeric)
        
2.  **customers** table:
    
    *   Columns: customer\_id (integer), name (text), country (text)
        

Tasks:

1.  Write a subquery to find the total number of orders placed by customers from the USA.
    
2.  Write a subquery to find the average total order amount placed by customers from Canada.
    
3.  Write a subquery to find the names of customers who have placed orders with a total amount greater than the average total order amount.
    

Sample Data:

**orders** table:

| order\_id | customer\_id | total\_amount |

|----------|-------------|--------------|

| 1 | 101 | 200.00 |

| 2 | 102 | 150.00 |

| 3 | 103 | 300.00 |

| 4 | 104 | 250.00 |

**customers** table:| customer\_id | name | country |

|-------------|--------|---------|

| 101 | John | USA |

| 102 | Alice | Canada |

| 103 | Bob | USA |

| 104 | Sarah | Canada |
