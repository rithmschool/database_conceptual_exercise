# Database Conceptual Exercise

Please answer the following questions (you can write your answers directly in this README file.)

1.  What is a relational database?

    A relational database is a way to model data as rows and columns in different tables.

1.  What is an RDBMS?

    Short for _relational database management system_, an RDBMS is a program that allows you to interact with data in your database. This includes adding, removing, and updating individual pieces of data, as well as changing the structure of the data.

1.  What is the difference between RDBMS and SQL?

    An RDBMS needs to use some language to access the database. SQL is the most popular language used by RDMBS's, but it's possible to have an RDBMS that uses a language other than SQL.

1.  What is the difference between a table and a schema?

    A table is a collection of rows and columns for a particular resource in your database (e.g. `users`, `messages`, or `books`.) A schema for a database is a description of how data in the database is structured. For instance, the schema defines things like what tables are in the database, what columns are in the tables, and what relationships exist between different tables.

1.  How do you connect to a database in psql?

    ```sql
    \c name_of_db
    ```

1.  How do you show all of your databases in psql?

    ```sql
    \l
    ```

1.  How do you create a database in psql?

    ```sql
    CREATE DATABASE name_of_db;
    ```

1.  How do you drop a database in psql?

    ```sql
    DROP DATABASE name_of_db;
    ```

1.  How do you create a database in the terminal?

    ```sh
    createdb name_of_db
    ```

1.  How do you drop a database in the terminal?

    ```sh
    dropdb name_of_db
    ```
