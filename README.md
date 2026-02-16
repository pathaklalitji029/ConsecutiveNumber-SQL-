# ConsecutiveNumber-SQL-

# Problem that we solved :-

In this problem, we are given a table called Logs that contains numbers along with their IDs. Our task is to find the numbers that appear at least three times in a row (consecutively).

# Apporach to solve :-

 1. We compare three consecutive rows at a time to find the consecutive number by sql.

 2. If the number in all three rows is the same, then it is a valid answer

 3. We use self join to compare current row with the next two rows

 4.DISTINCT is used to avoid duplicate results

 5. Then we find the Consecutive number using sql querry from table


# Space complexity :- O(n)

# Time complexity :- O(1)

