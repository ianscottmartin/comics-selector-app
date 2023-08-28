Project phase 3 Comic selector
OOP
users will be an]ble to look at a list of comics and their details
users will save a comic to their favorites
users can see one comic
users cans see their list of favorites
users can remove a comic form their favorites

OOP class for comic with attributes
class of USer with attributes

Database Tables
use sqlalchemy
Table: Users
-id
-email
-name?

Table: Comics
-id
-title
-publisher
-issue number

Table: association table between users and comics
-join table of relationship
-id
-user who liked it id

Type of relationship: one ot many user may have one or many to comics
comics can have a relationship of many to many between users
-realtionships
-user_comic_liked
-user can many fav comics
Comic can be liked by many users
user to comics = many to many relationship
How ot use lists and dictionaries Use a list to show the relationships between users and comics

Aggregate methods to project
-CRUD
-Create- create list(join table)
-Read
-display all comics
-display liked comics

    -Update-
    -Delete remove from list of liked

show a list of comics a user has. or relationship of comic with users

-user can have a list of comics as id's-join table
dictionary: comic has a set of attributes and values

Users:
-many to many relationship with comics
-id:integer not null primary key
-email string not null, unique
-name string not null , unique

Comics 
many to many relationship with users
-id integer not null unique primary key
-publisher string not null
-title string, integer

user liked comics

(join table)

-id integer not null primary key
-comic id integer not null
user who liked it id integer not null
