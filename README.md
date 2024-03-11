# SQL_Project_Music_Store_Analysis
# ABout this Project
Using SQL queries, this SQL project offers a thorough study of sales data from online music stores. You will learn everything from fundamental data extraction to sophisticated insights through this project. Structured question sets serve as the foundation for this study, directing the search across the music playlist database. I examined sales, consumer behaviour, genres, and other topics with three tiers of difficulty for my research.
# Database and Tools
- Postgre SQL
- PgAdmin4
# Schema Table
Prior to moving further, let's take a look at the music store's database, which has 11 tables. The schema diagram below illustrates all of the tables and how they relate to one another.
![music store database schema](https://github.com/shobkro/SQL_Project_Music_Store_Analysis/assets/39133098/21500bb6-22c2-477a-9617-4deca8a0f8bc)
# Questions
Question Set 1 - Easy
1. Who is the senior most employee based on job title?
2. Which countries have the most Invoices?
3. What are top 3 values of total invoice?
4. Which city has the best customers? We would like to throw a promotional Music 
Festival in the city we made the most money. Write a query that returns one city that 
has the highest sum of invoice totals. Return both the city name & sum of all invoice 
totals
5. Who is the best customer? The customer who has spent the most money will be 
declared the best customer. Write a query that returns the person who has spent the 
most money

Question Set 2 – Moderate
1. Write query to return the email, first name, last name, & Genre of all Rock Music 
listeners. Return your list ordered alphabetically by email starting with A
2. Let's invite the artists who have written the most rock music in our dataset. Write a 
query that returns the Artist name and total track count of the top 10 rock bands
3. Return all the track names that have a song length longer than the average song length. 
Return the Name and Milliseconds for each track. Order by the song length with the 
longest songs listed first

Question Set 3 – Advance
1. Find how much amount spent by each customer on artists? Write a query to return
customer name, artist name and total spent
2. We want to find out the most popular music Genre for each country. We determine the 
most popular genre as the genre with the highest amount of purchases. Write a query 
that returns each country along with the top Genre. For countries where the maximum 
number of purchases is shared return all Genres
3. Write a query that determines the customer that has spent the most on music for each 
country. Write a query that returns the country along with the top customer and how
much they spent. For countries where the top amount spent is shared, provide all 
customers who spent this amount
