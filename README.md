🎵 Music Store Database Analysis (MySQL)
A SQL-based data analysis project on a digital music store database. The goal is to answer real business questions using MySQL queries — ranging from basic lookups to advanced aggregations with CTEs and window functions.

📁 Files
FileDescriptionmusic_database_mysql.sqlFull database schema + data (MySQL)Music_Store_Query_MySQL.sqlAll analysis queries (MySQL)

🗄️ Database Schema
The database contains 11 tables:
employee · customer · invoice · invoice_line · track · album · artist · genre · media_type · playlist · playlist_track

❓ Questions Answered
Easy

Who is the senior most employee based on job title?
Which countries have the most invoices?
What are the top 3 highest invoice values?
Which city generated the most revenue? (best city for a Music Festival)
Who is the best customer by total spending?

Moderate

Find all Rock Music listeners (email, name) ordered alphabetically
Top 10 rock artists by number of tracks written
Tracks with above-average song length

Advanced

How much has each customer spent on each artist?
Most popular music genre per country
Top spending customer per country


🛠️ How to Use

Import music_database_mysql.sql into your MySQL server
Open and run queries from Music_Store_Query_MySQL.sql

sql-- Example
mysql -u root -p music_database < music_database_mysql.sql

🔧 Tools Used

Database: MySQL
Concepts: Joins, Subqueries, CTEs, Window Functions, Aggregations
