# Advanced-Database-Management-Systems-Course-Projects
CPSC 531 - Advanced Databases 
RDBMS and Database
The RDBMS for this project is the Datalog Educational System, or DES.
The database is Luis Rocha’s Chinook Database, modified for use with DES.

Loading the Database
Download the database file Chinook_DES.ddb and place it in the same directory where you extracted DES. The database can be loaded with the following command:
DES> /restore_ddb Chinook_DES.ddb
Note that the database will take a while to load. (On my laptop it takes about 30 seconds.)
You can view the database schema with /dbschema command, or by downloading and viewing Chinook_DES.sql.
Recreating the database
If the database does not load, you can recreate the database and save it again using the following commands:
DES> /process Chinook_DES.sql
DES> /save_ddb Chinook_DES.ddb
but note that this process will take several minutes to complete.

Queries
Write queries in Relational Algebra, Tuple Relational Calculus, and Domain Relational Calculus to determine each of the following:
1.	Albums by the artist “Red Hot Chili Peppers.”
2.	Genres associated with the artist “U2.”
3.	Names of tracks on playlist “Grunge” and their associated artists and albums.
4.	Names and email addresses of customers who bought tracks in playlist “TV Shows.”
5.	Names of the support representatives whose customers bought tracks in “Purchased AAC audio file” format.
