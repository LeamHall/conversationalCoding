# Database Connections

## Before you begin

This assumes you have read how to use databases with Go. For example:

	https://golang.org/doc/tutorial/database-access

There is a small SQLite database ( data/practicum.db ) in the repo. It contains one table, "stuff".
There are a few string entries with a row name of "thing" that you can use for the practicum. 
However, if you prefer a different database type, or want your own data, feel free to use it. 
These practices are for you.


## Package structure

Create a file called database.go.

Import something for printing, the database standard library, and the driver for your database of choice.

## Package Level Constructs

Create a struct with a string based attribute.


## Main

Create vars for the result sets and the data.

Create a connection to the database.
- Handle the error.
- Set it to close.

Pull a result, and print it.



