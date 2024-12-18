# PizzaStore-UI
## a Java UI for managing a database for a pizza store with PostgreSQL
Made by Hugo Centeno & Tyson Sakamoto

University of California Riverside

Last commit made on the 12th December 2024

  - ### About the project
    -This program was created to apply the knowledge adquired on relational databases.
    
    -The program is intended to run on a PostgreSQL server.
    
    -*/java/src/PizzaStore.java* contains the logic of the application.
    
    -*/data* contains all the data which is initially loaded. Later the user will be able to load its own data.
    
    -*/sql/src* contains the neccesary files to create the sql tables, load the data and optimize the queries via indexes.

  - ### Changes to make
    -To run the application changes need to be done in the file */sql/scripts/create_db.sh*, as originally the project ran on the server cs166_psql.
    
    -Once the DB is created on your PostgreSQL server, */java/scripts/compile.sh* with the correspondent changes will initilize the app.

  - ### What is next?
    -Forks suggesting changes to improve or extend the functionality of the application will be gratefully accepted.
    
    -To improve the user experience, the creation of a GUI will be considered. 
