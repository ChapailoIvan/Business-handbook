## Business-handbook

Handbook contains of two entities:

# Manufacture
 * name TEXT
 * country TEXT
 * email TEXT
 * website TEXT
 * zipCode INTEGER
 * foundingDate DATE
 * revenue NUMBER


# Spare part
 * manufacture FOREIGN KEY
 * code INTEGER
 * description TEXT
 * productionDate DATE
 * price NUMBER

@author: Chapailo Ivan, 4 group, 4th year, 2023
