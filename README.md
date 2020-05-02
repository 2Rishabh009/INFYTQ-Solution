# INFYTQ-SOLUTION
aLL INFYTQ SOLUTION OF DBMS,PYTHON,PYTTHON WITH DATASTRUCTURE AND PYTHON OOPS

Display month of sale and number of sales done in that month sorted in descending order of sales.

SOLUTION


select to_char(sldate,'Month') as month,count(sid) as NUMBER_SALE from sale 
  group by to_char(sldate,'Month') 
order by NUMBER_SALE desc
