# Songs-CS50

## Table of Contents 

- [Introduction](#introduction)
- [Features](#features)
- [Usage](#usage)
-  [Queries](#queries)
- [Requirements](#requirements)
- [License](#license)

  # Introduction
  
  This repository contains a set of SQLite queries to solve various problems related to a music database. The database consists of tables for songs and artists. You can use these 
  queries to extract and analyze data from the database.

  ## Note

  This was created as solution to the Lab Work to CS50 Course provided by Harvard University: https://cs50.harvard.edu/x/2023/labs/7/

  ## Features

  This program using:
  
  -  SQL queries to answer specific questions about the music database.
  - Instructions for running the queries using `sqlite3`.
  - Example queries for common data retrieval tasks.
 
 ## Usage
 
 To use this program and run the SQL queries, follow these steps:

1. Ensure you have `sqlite3` installed on your system.
2. Create an SQLite database with the tables `songs` and `artists` as specified in the program.
3. Create a separate SQL file for each query, such as `1.sql`, `2.sql`, etc.
4. Open your terminal or command prompt.
5. Navigate to the directory where your SQL files and database are located.
6. Run the SQL queries using the following command, replacing `filename.sql` with the query file and `songs.db` with your database:

   

`cat filename.sql | sqlite3 songs.db`


View the results in the terminal.

## Queries

Here is a list of the available SQL queries in this repository:

List the names of all songs in the database.
List the names of all songs in increasing order of tempo.
List the names of the top 5 longest songs, in descending order of length.
List the names of songs that have danceability, energy, and valence greater than 0.75.
Return the average energy of all the songs.
List the names of songs by Post Malone.
Return the average energy of songs by Drake.
List the names of the songs that feature other artists.
Feel free to explore and use these queries as needed.

## Requirements

sqlite3 for running the SQL queries.
An SQLite database with the tables songs and artists.

## License

This program is released under the MIT License.
