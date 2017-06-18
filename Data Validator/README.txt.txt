for format YYYY-MM-DD
^(18[0-9][0-9]|19[0-9][0-9]|20[0-9][0-9])-(0[1-9]|1[0-2])-(0[1-9]|1[0-9]|2|[0-9]|3[0-1])

for format DD-MM-YYYY
^(0[1-9]|1[0-9]|2|[0-9]|3[0-1])-(0[1-9]|1[0-2])-(18[0-9][0-9]|19[0-9][0-9]|20[0-9][0-9])

for format YY-MM-DD

^([0-9][0-9])-(0[1-9]|1[0-2])-(0[1-9]|1[0-9]|2|[0-9]|3[0-1])

for format DD-MM-YY
^(0[1-9]|1[0-9]|2|[0-9]|3[0-1])-(0[1-9]|1[0-2])-([0-9][0-9])


Changes which is needed at your end are :
1. change the dataabase connection.
2. Change the sample.csv if you want to.
3. create the table as per table ouput or use your the existing table in your db.