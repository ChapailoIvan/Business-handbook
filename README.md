### Business-handbook

Handbook contains of two entities:

## Manufacture:
 * name TEXT
 * country TEXT
 * email TEXT
 * website TEXT
 * zipCode INTEGER
 * foundingDate DATE
 * revenue NUMBER

## Spare part:
 * manufacture FOREIGN KEY
 * code INTEGER
 * description TEXT
 * productionDate DATE
 * price NUMBER

## About Database:
  Database is **SQLite** driven.  
  Database schema is placed [here](https://github.com/ChapailoIvan/Business-handbook/blob/main/schema/schema.txt).  
  Database initialization scripts are placed [here](https://github.com/ChapailoIvan/Business-handbook/blob/main/scripts/initialization.txt).
  
  Graphical representation of initialized tables: 
  * Manufacture:  
    ![Manufacture](/screenshots/manufacture.png)
  * Spare part:  
    ![Spare part](/screenshots/sparePart.png)
  



@author: Chapailo Ivan, 4 group, 4th year, 2023
