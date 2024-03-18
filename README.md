# Otrzymujemy i wyprowadzamy całą listę kontaktów w postaci tabeli (console.table)

node index.js --action list

![alt text](./screenshots/contactList.PNG)

# Otrzymujemy kontakt po id

node index.js --action get --id 05olLMgyVQdWRwgKfg5J6
![alt text](./screenshots/ContactId.PNG)

# Dodajemy kontakt

node index.js --action add --name Mango --email mango@gmail.com --phone 322-22-22
![alt text](./screenshots/AddContact.PNG)

# Usuwamy kontakt

node index.js --action remove --id qdggE76Jtbfd9eWJHrssH
![alt text](./screenshots/removeContact.PNG)
