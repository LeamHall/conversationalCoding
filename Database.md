# Database Connections

## Before you begin

This assumes you know how to use databases with your language. For example:

	https://golang.org/doc/tutorial/database-access
  https://sqlite.org/quickstart.html
  https://docs.python.org/3/library/sqlite3.html
  https://metacpan.org/pod/DBD::SQLite

There is a small SQLite database ( data/practicum.db ) in the repo. It contains one table, "stuff".
There are a few string entries with a row name of "thing" that you can use for the practicum. 
However, if you prefer a different database type, or want your own data, feel free to use it. 
These practices are for you.



Create a file called database with your language extension.

Create a structure with a string based attribute.

Create vars for the result sets and the data.

Create a connection to the database.
- Handle the error.
- Set it to close.

Pull a result, and print it.

