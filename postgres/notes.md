# PostGreSQL
----
## Using postgres with current user
```
sudo -u postgres psql
```
----

## Connecting to Database
```
\c databaseName;
```

## List database tables
```
\dt;
```

## Creating a Database
```
createdb databaseName;
```

## Creating a Table
```
CREATE TABLE (name_of_column type, name_of_column, type);
```

###
Options for Values when creating a table
- Types
  - integer
  - timestamp
  - text
  - varchar(100) // integer is limit of characters, 100 is an example
  - bigserial
  - date
  - char(5)
  - interval hour to minute

- Parameters
  - NULL
  - NOT NULL
  - CHECK (runs condition)
  - DEFAULT (default data)

----

### Example:
```
CREATE TABLE myTable(id varchar(60) PRIMARY KEY, name varchar(100) NOT NULL, joined bigint, bio varchar(250));
```

## Common Commands
### Quit
```
\q
```
### 

