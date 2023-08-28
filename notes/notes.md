Project phase 3 Comic selector
OOP
users will be an]ble to look at a list of comics and their details
users will save a comic to their favorites
users can see one comic
users cans see their list of favorites
users can remove a comic form their favorites

OOP calss for comic with attributes
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
    Cmic can be liekd by many users
    user to comics = many to many relationship
How ot use lists and dictionaries Use a list to show the relationships between users and comics

Aggregate methods to project
    -CRUD
    _create- create list(join table)
    -Read 
        -display all comics
        -display liked comics

    -Update- 
    -Delete remove from list of liked
show a list of comics a user has. or relationship of comic with users

-user can have a list of comics as id's-join table
dictionary: comic has a set of attributes and values

