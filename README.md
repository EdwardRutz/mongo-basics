# Mongo Database Basics

>Exploring MongoDB using a database of blog posts for a blog.


- Mongo is a No-SQL database
- No SQL = Not Only SQL
- Store data in multiple formats and less bound by schema controls
- Documents are individual records that store data
- Documents can store references to other documents.
- Collections organize a group of documents

## Setup the database

- Install MongoDb
- Run the seed file, `seed.js`

## Running Mongo

### Create a directory where MongoDB will store it’s files. 

- From the command prompt run md \data\db. This is the default location. 
- Other locations can be specified using the --dbpath parameter. 

### Run Mongo
- Start mongodb daemon, run C:\mongodb\bin\mongod.exe in the Command Prompt. 

- Connect to MongoDB using the Mongo shell 
- While the MongoDB daemon is running, from a different Command prompt window run C:\mongodb\bin\mongo.exe


## Mongo Shell Commands

- List databases, `show dbs`
- Create datbase mongoBasics, `use mongoBasics`
- Add data into the local database, `db.post.insert({title: "hooray"})
- `show collections`
- List documents in a collection, `db.post.find()`
- load('./path/to/seed.js'),  `load('seed.js')`
- `db.getCollectionNames()`
- Show users, 'db.users.find()'
- Count users, `db.users.count()`
- Count log posts, `db.posts.count()`



## Sources

- [Treehouse Tutorial: Mongo Basics (87 minutes)](https://teamtreehouse.com/library/mongo-basics)
- [Mongo Docs](https://docs.mongodb.com/)
- [Install Mongo in Windows](http://treehouse.github.io/installation-guides/windows/mongo-windows.html)
- [Mongo 4 Manual](https://docs.mongodb.com/manual/)
- [MongoDB: What is No SQL](https://www.mongodb.com/nosql-explained)
- [Terminology: No SQL Compared to SQL](https://docs.mongodb.com/manual/reference/sql-comparison/)
- [Mongo Docs: load()](https://docs.mongodb.com/master/reference/method/load/)
- [Mongo Docs: Timestamps](https://docs.mongodb.com/manual/reference/bson-types/#timestamps)



