# lab-sql-8
lab-sql-8
In this lab, you will be using the Sakila database of movie rentals. You have been using this database for a couple labs already, but if you need to get the data again, refer to the official installation link.

The database is structured as follows: DB schema

Instructions
Rank films by length (filter out the rows with nulls or zeros in length column). Select only columns title, length and rank in your output.
Rank films by length within the rating category (filter out the rows with nulls or zeros in length column). In your output, only select the columns title, length, rating and rank.
How many films are there for each of the categories in the category table? Hint: Use appropriate join between the tables "category" and "film_category".
Which actor has appeared in the most films? Hint: You can create a join between the tables "actor" and "film actor" and count the number of times an actor appears.
Which is the most active customer (the customer that has rented the most number of films)? Hint: Use appropriate join between the tables "customer" and "rental" and count the rental_id for each customer.
Bonus: Which is the most rented film? (The answer is Bucket Brotherhood).

This query might require using more than one join statement. Give it a try. We will talk about queries with multiple join statements later in the lessons.

Hint: You can use join between three tables - "Film", "Inventory", and "Rental" and count the rental ids for each film.
