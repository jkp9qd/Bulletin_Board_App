# bulletin_board_app

Goal
Develop a website which can efficiently store and retrieve user submitted messages from a PostgreSQL database.

Assignment
Back in the late 90's, writing in an online guestbook or message board was the thing to do!

For this assignment, let's recreate this pasttime activity by developing a website that allows people to post messages to a page. A message should consist of a title and a body. The site should have two pages:

The first page shows people a form where they can add a new message.
The second page shows each of the messages people have posted.
Make sure there's a way to navigate the site so users can access each page.

Messages must be stored in a postgres database. Create a table called messages, with the following column names and data types:

Column Name	Column Data Type
id	serial primary key
title	text
body	text
Grading Criteria
The database is named bulletinboard.
The postgres username must be read from an environment variable named POSTGRES_USER.
The postgres password (if present) must be read from an environment variable named POSTGRES_PASSWORD
The table is called messages.
The messages table consists of an id, title and body column.
The first page consists of a form where users can add a message.
The second page displays the submitted messages.
Submit the assignment in a zipped project folder.
