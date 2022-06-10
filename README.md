# WebBackend_Project1
Wordle Game Backend Services

In this project I have build two RESTful back-end microservices.

The following are the learning goals for this project:

1.Designing back-end APIs for a web application given a description of their functionality.

2.Implementing back-end APIs in Python with the FastAPI web framework.

3.Designing and implementing relational database schemas for back-end APIs.

4.Extracting, transforming, and loading databases given data sources in other formats.

5.Creating Procfile descriptions for web service processes.

Libraries, Tools, and Code

This project must be implemented in Python using the FastAPI framework and ancillary tools such as Foreman and the sqlite3 command line tool. 
Database code must use the sqlite3 module from the Python Standard Library

Services

Create two RESTful microservices, one for the word list of valid guesses and one for checking guesses against answers.

The word validation service should expose the following operations:

Checking if a guess is a valid five-letter word

Adding and removing possible guesses

The answer checking service should expose the following operations:

Checking a valid guess against the answer for the current day.

If the guess is incorrect, the response should identify the letters that are:

in the word and in the correct spot,

in the word but in the wrong spot, and

not in the word in any spot




