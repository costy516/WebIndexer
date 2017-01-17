# WebIndexer
This project is to index sites on the internet and to create a database of the results.

Java will be used to with three queues to concurrently create the database.  The first queue will be to create the String of the domain name.  The second queue will take items in the first queue and use different TLDs and check to see if a connection can be made.  If a connection is made the string gets stored in a third queue.  Items will be taken from the third queue and will have items taken to create an entry in the database.

A front end has not yet be decided for this project.
