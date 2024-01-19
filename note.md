# Overview
Crucial
- Installation
- Mongo Shell
- Mongo CRUD
  
Important
- Database basics
- SQL and No-SQL

# MongoDB
- SQL and Non-SQL
  - SQL would use relational table
  - No-SQL is diverse
- Use JSON
```js
[
    {
        "id": 1,
        "author": "Mae",
        "text" : "Hello World",
        "comment": [
            "jack": "Thats cool",
            "john": "So true"
        ]
    },
    {
        "id": 2,
        "author": "John",
        "text" : "World Hello",
        "comment": [
            "Mae": "Huhu hihi hehe",
            "john": "So true"
        ]
    }
]
```
# Installing MongoDB
- Install shell
- Install MongoDB Compass

# Basic Mongo Syntax
- Mongosh syntax
  - help
  - db
  - show dbs
  - use <dbName>

# Mongosh tips and trick
  - Basically a JS shell

# BSON
- Just like JSON

# Insert
- db.<collection>.insert()
  - Can insert one
  - Can insert arrays of obj 

# Query
- db.<>.find()      -> List all
- db.<>.find({key:value})
- db.<>.findOne({key:value})

# Updating
- db.<>.updateOne({<key>:<value>}, {$set: {<key>:<value>}})
- db.<>.updateMany({<key>:<value>}, {$set: {<key>:<value>}})
  - $set
  - $currentDate: {lastModified: true}