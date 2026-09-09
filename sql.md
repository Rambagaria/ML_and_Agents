Order of Execution-
F - FROM / JOIN
W - WHERE
G - GROUP BY
H - HAVING
S - SELECT
D - DISTINCT
O - ORDER BY
L - LIMIT
(Fresh Waffles Give Happiness, So Do Our Lattes)

LEFT JOIN returns only unmatched rows from the left table, as well as matched rows in both tables.

RIGHT JOIN returns only unmatched rows from the right table , as well as matched rows in both tables.

FULL OUTER JOIN returns unmatched rows from both tables,as well as matched rows in both tables.

COUNT(*): Counts all rows in a table, including rows with NULL values.  

COUNT(column_name): Counts only the non-null values in that specific column, ignoring any NULL entries.

AVG is a SQL aggregate function that calculates the average of a selected group of values. It's very useful, but has some limitations. First, it can only be used on numerical columns. Second, it ignores nulls completely.

SUM is a SQL aggregate function. that totals the values in a given column. Unlike COUNT, you can only use SUM on columns containing numerical values.

Where clause doesn't allow to filter on aggregate columns, that's where the HAVING clause comes in.

A window function performs a calculation across a set of table rows that are somehow related to the current row. This is comparable to the type of calculation that can be done with an aggregate function. But unlike regular aggregate functions, use of a window function does not cause rows to become grouped into a single output row — the rows retain their separate identities. Behind the scenes, the window function is able to access more than just the current row of the query result.

In window functions, Order By creates a running total. Without order by, it will be directly partitioned and summed for this example:  

SELECT start_terminal,\
       duration_seconds,\
       SUM(duration_seconds) OVER\
         (PARTITION BY start_terminal ORDER BY start_time)\
         AS running_total\
  FROM tutorial.dc_bikeshare_q1_2012\
 WHERE start_time < '2012-01-08'

 RANK, ROW_NUMBER, DENSE_RANK, LAG, LEAD, SUM, COUNT, AVG

 SOLVED LEET CODE QUESTIONS:

595 - Big Countries
584 - Find Customer Referee
1757 - Recyclable and Low Fat Products
1378 - Replace Employee ID With The Unique Identifier
197 - Rising Temperature
577 - Employee Bonus
1075 - Project Employees I
620 - Not Boring Movies
178 -  Rank Scores
626 - Exchange Seats