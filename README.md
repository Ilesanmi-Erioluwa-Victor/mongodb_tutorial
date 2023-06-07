## What is MongoDB ?
Mongodb is mostly important database server that allows you to run different databases on it.
MongoDB is so called no SQL solution because it's basically following an opposite concept or philosophy.
A record in MongoDB is a document, which is a data structure composed of field and value pairs. MongoDB documents are similar to JSON objects. The values of fields may include other documents, arrays, and arrays of documents.

### Installing MongoDB on windows systems
You can install MongoDB on windows by visiting this link
[MongoDB installation on windows](https://www.mongodb.com/try/download/community), by defaults, your windows Operating system will be pre selected.
[MongoDB shell download](https://www.mongodb.com/docs/mongodb-shell/install/), follow this instructions to also install MongoDB shell on window.

### MongoDB Commands
Below are MongoDB commands, which you can use in your MongoDB shell

| Commands | Uses |
| --------------- | -------------- |
| **`show dbs`** | To display list of databases on your shell, e.g `show dbs`, by defaults it's will display three databases which are `admin`, `local`, `config` |
| **`use`**      | To switch between databases on your shell e.g `use shop`, automatically, it will create a shop database for you.|
| **`db.`**      | To create a collection in your database, the `.` suffix, that's where you will insert your collection name e.g `db.products`, it will create products collection for you automatically in your db.  |


### DOCUMENT AND CRUD BASICS 
