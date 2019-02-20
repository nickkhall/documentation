# PostGreSQL
----
## Using postgres with current user
```
sudo -u postgres psql
```
----

## Creating a Database
```
createdb databaseName;
```

## Connecting to Database
```
\c databaseName;
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

## Common Commands
### Quit
```
\q
```
### 

