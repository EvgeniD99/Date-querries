# Date-querries for MS ACCESS 
MS ACCESS SQL (date querries) 
#Query for returning hour 
SELECT format(column_name,"hh:nn") AS desired name , * 
From TABLE
WHERE column in 
#
#
#
#
#what to know if hour is on or not 

SELECT format(column_name,"hh:nn") AS desired_name, DateDiff('d',first_date,last_date) AS desired_name, *,IIF ( format(column_date,"hh:nn") < "12:00" ,'On time','Not on time') AS desired_name
FROM TABLE
WHERE DateDiff('d',first_date,last_dte) in (...) 



