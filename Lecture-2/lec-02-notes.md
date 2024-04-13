### Lecture 2 - DBMS Architecture

- [Lecture 2 Notes and Slides](https://github.com/vishpant76/Complete-DBMS-Notes-CodeHelp/tree/master/Lecture%202) - Find the full notes and lecture slides PDFs here.

- Abstraction in DBMS.
- Three Schema Architecture.
- Schema? - It's just a design.
- Physical level - Describes how the data is stored physically in disks.
- Logical/Conceptual level
- View Level - for user. has View schema
- Data Models - describing design of DB at logical level.
- How app access DB? - Using an interace/ an API using which we write application code that interacts/comunicates with the DB to perform data base actions. E.g JDBC in Java, ODBC for C++ etc.
- What are the various roles/functiosn of DBA?
- DBMS Application Architecture.
- Tier 1 Architecture - client, server, and DB all three on same machine. e.g when we build an app on localhost.
- Tier 2 Architecture - Application invokes direct DB call over the network which goes to the database on the server. May be this is the one used in AMUSE, SPI, etc in Wood ?
- Tier 3 Architecture - app partitioned into 3 logical components. Client machine is just a front end, and the app doesn't invoke any direct DB calls. Client communicates with app server, and the app server in turn communicates with db. used in www apps, that need to be scaled.

- 
