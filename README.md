# [✨] Zokuru Database
A project born out of boredom

## [💫] What is the function of this package?
> This is a package that can help manage databases with local storage

## [❄️] How to use this package?
You need to import `ZokuDB` from this package
```js
const { ZokuDB } = require("@zokuru/database");
```
Now, let's setup your database
```js
const database = new ZokuDB({
  dbFolder: "zokuru",
  dbName: "database",
  noBlankData: true // Optional.
  readable: true // Optional.
});
```
> `dbFolder` is the name of the folder to store your database files, and `dbName` is the name of the database file.

From the above example, I created a database with a folder named "zokuru", and a file named "database"
This will create a new (or existing) database file with a directory `./zokuru/database.json`

And, here is a list of methods that can be used on `ZokuDB`:
[null]

# 
### [☁️] This `README.md` will be updated soon
```js
npm i https://github.com/zokuru/database.git
```
