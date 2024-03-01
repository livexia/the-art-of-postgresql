# Chapter 1 Structured Query Language

### Loading the Data Set

psql's -s option puts you in single step mode which pauses before sending each statement to the server.

`psql -U livexia -h 127.0.0.1 -p 5432 mydb -s -f factbook.sql`
