As a busy user
So I can quickly go to my websites
I want to see a list of bookmarks

As a busy user
So I can retrive a bookmark later
I want to add a new bookmark


### To set up the database
 Connect to `psql` and create the `bookmark_manager` database:
 ```
CREATE DATABASE bookmark_manager;
```
 To set up the appropriate tables, connect to the database in `psql` and run the SQL scripts in the `db/migrations` folder in the given order.
