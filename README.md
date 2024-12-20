# Invoice_Program

Here, I am fetching the invoice json file through streaming environment to adls, then cleaning the invoice json file and 
applying some transformation logic(like flattern the object columns into respective each columns) on fields and
filter only needed fields and writting the streaming data into delta tables in append mode.

For testing purpose, I am created testcases to do automation testing on it.