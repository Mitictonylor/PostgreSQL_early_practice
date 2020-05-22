PostgreSQL practice
Codeclan week3 day1

#SQL Homework

**BRIEF**

The Springfield Cinema is having a Marvel Movie Marathon! They have asked you to help maintain their database of movies with times and attendees.

To access the database:
First, create a database called ‘marvel’

terminal
createdb marvel
Next, run the provided SQL script to populate your database:

terminal
psql -d marvel -f marvel.sql
Use the supplied data as the source of data to answer the questions. Copy the SQL command you have used to get the answer, and paste it below the question, along with the result they gave.

**Questions**

- Return ALL the data in the ‘movies’ table.
- Return ONLY the name column from the ‘people’ table
- Change Krusty's name to reflect the proper spelling
- Return ONLY Homer Simpson’s name from the ‘people’ table
- Batman is DC, not Marvel! Delete the entry from the ‘movies’ table
- Add Bart Simpson to the ‘people’ table
- Remove Eric Cartman from the table of people
- Add an exclusive midnight showing of ‘Avengers: Infinity War’
- Make the Iron Man movies a triple billing

**Extension**

Research how to delete multiple entries from your table in a single command.
