# Date-querries for MS ACCESS 
MS ACCESS SQL (date querries) 
#Query for returning hour 
SELECT format(column_name,"hh:nn") AS desired name , * 
From TABLE
WHERE column in 
#
#
#
##
# want to know if hour is on time or not on time 

SELECT format(column_name,"hh:nn") AS desired_name, DateDiff('d',first_date,last_date) AS desired_name, *,IIF ( format(column_date,"hh:nn") < "12:00" ,'On time','Not on time') AS desired_name
FROM TABLE
WHERE DateDiff('d',first_date,last_dte) in (...) 
##
##
# FOR query performance write where clauses with JOIN's, in the current example is a DATE from the past 12 months. 

Select * 
 FROM table1
  INNER
   JOIN table 2
     ON table1_column_id = table2_columnid and date > DATEADD(month,-12,getdate())
     
#Using between clause in MS ACESS 

select 
CONVERT(DATE, DATEADD(mi, DATEDIFF(mi, table1.datecolumn AT TIME ZONE 'W. Europe Standard Time', table1.datecolumn), table1.datecolumn)) AS DATE,
column1,
column2,
column3,
column4,
column5,
column6,
column7

from table1


where column1 LIKE '%RCPT%'
AND  DATE BETWEEN '10/01/2021' AND '12/31/2021'


