# PostGreSQL
----
## Using postgres with `postgres` user
```
sudo -u postgres psql
```
----

## Listing Databases
```
\l
```
--- *or* ---
```
\list
```

## Connecting to Database
```
\c databaseName;
```

## Creating a Database
*note*: **MUST** have a semi-colon at the end.
```
create database myDbNameHere;
```

## Listing contents of table
```
\d databaseName;
```

## List database tables
```
\dt;
```

## View Table Data
```
table tableName;
```

## Creating a Table
```
CREATE TABLE table_name_here (name_of_column type, name_of_column, type);
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

## Deleting Table
```
DROP TABLE myTable;
```

## Common Commands
### Quit
```
\q
```
### 

