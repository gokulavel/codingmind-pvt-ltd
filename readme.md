1.What is an API ?
API is the messenger  that takes request and tell to  the system what you want to do and then returns the response back to you to.
for example-API is the waiter in hotel get a request from a customer,that request food passes to the chef.he prepared then give it to the waiter to serve food to customer. 

2.What is REST and which methods are there in REST ?
If you have used Any modern website then chances are you have interacted with the website that uses rest. 
Even YouTube uses Restful URLs on It’s site but what exactly is rest for starters rest stands for REPRESENTATIONAL STATE TRANSFER.
It’s just a fancy way of saying that a server response to create read update and delete request in a standard way the idea behind rest is to treat all server URL‘s as access Points for the various resources on the servers

3.Which REST method will be cached in browser unless otherwise explicitly mentioned by
server ?

GET strategy will be catched in program except if in any case unequivocally referenced by server.
The GET strategy is utilized to peruse or retrival.Get technique returns XML or JSON representation.
In blunder case it returns 400(bad solicitation) or 404 error(not found).

4.Which REST method is idempotent and which method is not idempotent ? Explain with a
small example.
POST is an idempotent strategy… .Example:A customer needs to refresh assets through POST.Since it is an idempotent calling results in incorrect.It is known as sheltered techniques.

HTTP is non-idempotent..Example:To get to a database or picture from HTML page JSP page tales,we use GET method,it will return same object.If we need to get to database like client data we need to utilize POST technique.
Idempotent :
int d=5;
Not idempotent  :
d++;

5.Which REST method should be used to deal with user sensitive data like credit card
information etc. ?
The method used to deal with the user senstive data like credit card and information is PATCH method in REST method.It is also called as a request method in which it provides an entity containing a 
list of changes applied to a particular resource requested using an HTTP url.

6.What is the difference between http and https ? Explain shortly how https works.
HTTP
----------------------- 
1,http is operated on application layer
2,port number 80 is used for communication
3,No encryption is there
4,Unsecured.
5,No SSL certificates are required for HTTP

HTTPS
------------------------
1,https is operated onTransport layer.               
2,Port number 443 is used for communication.
3,Encryption is used.
4,Secured.
5,HTTPS it is required that you have an SSL certificate and it is signed by a CA.

HTTPS takes the well-known HTTP protocol, and simply layers a SSL/TLS (hereafter referred to simply as “SSL”) encryption layer on top of it.
Servers and clients still speak exactly the same HTTP to each other, but over a secure SSL connection that encrypts and decrypts their requests and responses

7.What is caching ? How does it help an application ?
Caching refers to storing the result of operation so that future request returns faster.
How does it help an application
--------------------------------
Computation is slow.
Competition will run multiple time.
When the output is the same for a particular input.
You hosting provider charges for database access.

8.What is the main difference between traditional relational databases and nosql databases ?

traditional relational databases
----------------------------------------
1,RDBMS is completely structured way of storing data.
2,the amount of data stored mainly depends on the Physical memory of the system.
3,SQL databases have fixed or static or predefined schema
4,SQL databases are best suited for complex queries
5,MySQL, Oracle, Sqlite, PostgreSQL and MS-SQL etc. are the example of SQL database

nosql databases
-----------------------------------------
1,NoSQL is unstructured way of storing the data
2,the NoSQL you don't have any such limits as you can scale the system horizontally.
3,NoSQL databases have dynamic schema.
4,MongoDB, BigTable, Redis, RavenDB, Cassandra, Hbase, Neo4j, CouchDB etc. are the example of nosql database
5,NoSQL databases are not so good for complex queries because these are not as powerful as SQL queries.

9.Explain shortly MVC pattern in developing backend applications.

MVC is the model view controller it’s a software architectural design pattern one of the most frequently used patterns 
separate application functionality promotes organised a programming

10.What is event loop in javascript ? Explain with an example

The event loop continuously checks the call stack to see if there's any function that needs to run.
While doing so, it adds any function call it finds to the call stack and executes each one in order.
EXAMPLE:
In application The event loop dequeue first message to global eval:int
Then   call it’s callback to call stack
In the call stack  link.addEventListener propose click to change colour
After we click it’s goes to implementation  specific
In the implementation specific It order when someone click the link enqueue a message.
Then it will move to click change colour in message queue

11.What is the difference between git pull and git fetch ?

git pull
---------------------------------
If you do a git pull, 
it will do basically fetch (as explained previously) and merge any new changes to your master branch and move the pointer to HEAD.

when you do a git pull, it gets all the changes from the remote or central repository and attaches it to your corresponding branch in your local repository.

git fetch
-------------------------------------------
If you do a git fetch it will just fetch all the changes in the remote repository (Github) and move the origin/master pointer to HEAD. 
Meanwhile your local branch master will keep pointing to where it has.

when you do a git fetch, it gets all the changes from the remote repository, stores the changes in a separate branch in your local repository 
and if you want to reflect those changes in your corresponding branches, use a git merge to do that.