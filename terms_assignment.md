### 1:-10 popular commands - daily use

cd --(change directory)
mkdir or dir --(make new directory)
rd ---(remove directory)
ni <give name to item> --(create new file)
ri <item name> --(remove file)
ls or dir --(shows all directories and files in that directory)
cls --(clear command line screen)
more <file name>  --(read the file)
mv <file> <destination> --(move the file to some destination)
exit

### 2:-10 popular network commands

ping <hostname> check the network connection
ipconfig (it gives all the connections)
netstat	(it give stats on all network activities)
tracert (trace the route that a packet takes to reach the destination )
pathping <hostname> it identify which routers are on path
hostname (gives the name of the host)
getmac (shows the MAC address of network interfaces)
nslookup (troubleshoot DNS)
route 
finger

### 3:- 10 OS commands 

cls
shutdown 
systeminfo
tree (show the folder content in tree format)
cd (change directory)
mkdir (make new directory)
copy <file> <destination>
tasklist (shows all the task that are running in the device)
taskill /IM taskname /F(will kill the the task that is running)
exit


### 4:-10 popular Git commands

git init - Turn an existing directory into a git repository
git log — See all commit history
git status - see what changed since last commit
git add <file name> - add file
git commit -m “message” - commit our changes
git add . - add all files
git diff - shows what changes you made since last commit.
git push -u origin master - push all the contents
git merge <file> - To merge branch with master branch.
git remote add origin <link>


### 5:- Database

Database are data structure that stores information (mostly in form of tables )


### 6:-SQL Database

SQL(structured query language) we use SQL statement to operate on Database (operation like update delete get data etc from Database)

### 7:-NoSQL Database

NoSQL are Non-relational DMS. SQL are table based databases but NoSQL Databases can be key-value pairs,graph databases or document based databases.
It uses dynamic schema for unstructured data

### 8:-10 popular databases

MYSQL,
Postgres,
mongoDB,
Oracle,
MariaDB,
MS SQL,
AmazonRDS,
Redis,
Cassandra,
Elasticsearch


### 9:-ACID(Atomicity Consistency Isolation Durability)

It's a property of sql which ensure Data Integrity during a transaction.

ATOMICITY- it means either all the operation in a transaction take place or none should take place 
CONSISTENCY -means that if the transaction is successfully then it changes the databases or if there is some error during the transaction 
			it will restore database before the transaction
ISOLATION -means every transaction is individual and can't access the result of other transaction until the transaction is completed
DURABILITY - means if the transaction is completed then it is updated to the database.then after if system fails then also data will safely in the database

### 10:-Aggregations

Data aggregation is any process in which information is gathered and expressed in a summary form, for purposes such as statistical analysis.
A common aggregation purpose is to get more information about particular groups based on specific variables such as age, profession, or income.
 
### 11:-Joins

INNER JOIN: Returns data that have matching values in both tables
LEFT JOIN: Returns all data from the left table, and the matched data from the right table
RIGHT JOIN: Returns all data from the right table, and the matched data from the left table
FULL JOIN: Returns all data when there is a match in either left or right table


### 13:-CAP THEOREM

CAP Theorem is a concept that a distributed database system can only have 2 of the 3: Consistency, Availability and Partition Tolerance

### 14:-Normalization

Normalization is a database design technique which organizes tables in a manner that reduces redundancy and dependency of data. 
It divides larger tables to smaller tables and links them using relationships. 

### 15:-Database Sharding

Database Sharding involves breaking the data into smaller chunks called logical shards.
this shards can be a seperate RDBMS server.
this makes the data retrieve faster;

### 16:-7 network layers

Layer 1 - Physical(cables, cards and physical aspects)
Layer 2 - Data Link.
Layer 3 - Network.
Layer 4 - Transport.
Layer 5 - Session.
Layer 6 - Presentation.
Layer 7 - Application(WWW browsers, NFS, HTTP )

### 17:-Request Response Protocol

HTTP works as a request-response protocol between a client and server. 
Example: A client (browser) submits an HTTP request to the server; then the server returns a response to the client. 
The response contains status information about the request and may also contain the requested content.


### 18:-Web API

A Web API is an application programming interface for either a web server or a web browser. It is a web development concept, usually limited to a web application's client-side ,
 and thus usually does not include web server or browser implementation details such as SAPIs or APIs unless publicly accessible by a remote web application. 

### 19:-REST

Representational state transfer is a software architectural style that defines a set of constraints to be used for creating Web services.
Web services that conform to the REST architectural style, called RESTful Web services, provide interoperability between computer systems on the Internet.

### 20:-HTTP Status Codes to Handle

200 (OK)
201 (Created)
202 (Accepted)
204 (No Content)
302 (Found)
304 (Not Modified)
400 (Bad Request)
401 (Unauthorized)
403 (Forbidden)
404 (Not Found)
500 (Internal Server Error)


### 21:-HTML

Hypertext Markup Language is the standard markup language for documents designed to be displayed in a web browser. 
It can be assisted by technologies such as CSS and scripting languages such as JavaScript


### 22:-Box Model

Box Model is essentially a box that wraps around every HTML element.
It consists of: margins, borders, padding, and the actual content.

### 23:-Margin

The CSS margin properties are used to create space around elements, outside of any defined borders.
--properties
margin-top
margin-right
margin-bottom
margin-left
--units
auto
length - specifies a margin in px, pt, cm, etc.
% - specifies a margin in % of the width of the containing element

### 24:-Padding

CSS padding properties are used to generate space around an element's content, inside of any defined borders
--properties
padding-top
padding-right
padding-bottom
padding-left
--units
length - specifies a padding in px, pt, cm, etc.
% - specifies a padding in % of the width of the containing elemen

### 25:-CSS Selectors

CSS selectors are used to "find" the HTML elements you want to style

Simple selectors (select elements based on name, id, class)
Combinator selectors (select elements based on a specific relationship between them)
Pseudo-class selectors (select elements based on a certain state)
Pseudo-elements selectors (select and style a part of an element)
Attribute selectors (select elements based on an attribute or attribute value)


### 26:-CSS Specificity

Think of specificity as a score/rank that determines which style declarations are ultimately applied to an element
Specificity Hierarchy  and points
1000--Inline styles
100 --IDs
10--Classes, attributes and pseudo-classes 
1 --Elements and pseudo-elements


### 27:-Flexbox

four layout modes
Block, for sections in a webpage
Inline, for text
Table, for two-dimensional table data
Positioned, for explicit position of an element
The Flexible Box Layout Module, makes it easier to design flexible responsive layout structure without using float or positioning


### 28:-Grid

The CSS Grid Layout Module offers a grid-based layout system, 
with rows and columns, making it easier to design web pages without having to use floats and positioning.
An HTML element becomes a grid container when its display property is set to grid or inline-grid.


### 29:-Git

Git is a distributed version-control system for tracking changes in source code during software development. It is designed for coordinating work among programmers, 


### 30:-HTTP(HyperText Transfer Protocol) 

HTTP is the underlying protocol used by the World Wide Web and this protocol defines how messages are formatted and 
transmitted, and what actions Web servers and browsers should take in response to various commands


### 31:-TCP

TCP (Transmission Control Protocol) is a standard that defines how to establish and maintain a network conversation through which application programs can exchange data. 
TCP works with the Internet Protocol (IP), which defines how computers send packets of data to each other

### 32:-UDP

UDP (User Datagram Protocol) is an alternative communications protocol to Transmission Control Protocol (TCP) used primarily for establishing low-latency and 
loss-tolerating connections between applications on the internet

### 33:-Web server
web server is to store, process and deliver web pages to clients.
 
### 34:-Static server

Static server is a simple http server to serve static resource files from a local directory and sends its hosted files "as-is" to your browser

###  35:-Application server(appserver)
an application server is a program that handles all application operations between users and an organization's backend business applications or databases


### 36:-DNS server
A DNS server is a computer server that contains a database of public IP addresses and their associated hostnames, and in most cases serves to resolve, 
or translate, those names to IP addresses as requested.

### 37:-Database Server
A database server is a server which uses a database application that provides database services to other computer programs or to computers


### 38:-Standalone Application
A standalone application is one which does not have to be integrated with other applications to function.
example:-
Vlc media player
Adobe photoshop
Notepad++


### 39:-MVC
Model–view–controller is a software design pattern commonly used for developing user interfaces which divides the related program logic into three interconnected elements. 
This is done to separate internal representations of information from the ways information is presented to and accepted from the user

### 40:- Operating System
An Operating System (OS) is an interface between a computer user and computer hardware
it manages computer hardware, software resources, and provides common services for computer programs.

### 41:-Kernel
A Kernel is the central part of an operating system. It manages the operations of the computer and the hardware - most notably memory and CPU time.

### 42:-process
a process is the instance of a computer program that is being executed by one or many threads


### 43:-Thread
A thread is the smallest unit of processing that can be performed in an OS. 
In most modern operating systems, a thread exists within a process - that is, a single process may contain multiple threads


### 44:-SOLID
S-Single responsibility principle(A class should only have a single responsibility)
O-Open–closed principle(open for extension, but closed for modification)
L-Liskov substitution principle(Objects in a program should be replaceable with instances of 									their subtypes without altering the correctness of that program.)
I-Interface segregation principle(Many client-specific interfaces are better than one 		general-purpose interface)
D-Dependency inversion principle(One should "depend upon abstractions, [not] concretions)

### 45:-Apache Web Server
Apache Wev Server is like a middleman between server and the client machine.it pulls the content
from the server on user request and deliver it to the web

Apache is an open-source and free web server software that powers around 46% of websites around the world

### 46:-Nginx Web Server


### 47:-Messaging Queue
Message queuing allows applications to communicate by sending messages to each other. 
The message queue provides temporary message storage when the destination program is busy or not connected.

### 48:-enterprise service bus (ESB)
An enterprise service bus (ESB) is a middleware tool used to distribute work among connected components of an application. 
ESBs are designed to provide a uniform means of moving work, offering applications the ability to connect to the bus and subscribe to 
messages based on simple structural and business policy rules 

### 49:-RabbitMQ
RabbitMQ is a general purpose messaging solution, often used to allow web servers to respond to requests quickly instead of being 
forced to perform resource-heavy procedures while the user waits for the result

### 50:-Kafka
Apache Kafka is a distributed streaming platform capable of handling trillions of events a day. Kafka provides low-latency, high-throughput, 
fault-tolerant publish and subscribe pipelines and is able to process streams of events


### 51:-Zookeeper
Apache ZooKeeper is a software project of the Apache Software Foundation. It is essentially a service for distributed systems offering a hierarchical key-value store, 
which is used to provide a distributed configuration service, synchronization service, and naming registry for large distributed systems


### 52:-Service-oriented architecture (SOA)
Service-oriented architecture (SOA) is a style of software design where services are provided to the other components by application components, 
through a communication protocol over a network. The basic principles of service-oriented architecture are independent of vendors, products and technologies.


### 53:-Redis? Why?
Redis is an open source (BSD licensed), in-memory data structure store, used as a database, cache and message broker.
Redis data structures resolve very complex programming problems with simple commands executed within the data store, 
reducing coding effort, increasing throughput, and reducing latency

### 54:-Solr? Why?(Shareable Online Learning Resources )
Solr is used for full-text search, hit highlighting, faceted search, real-time indexing, dynamic clustering, database integration, 
NoSQL features and rich document handling.

### 55:-ElasticSearch? Why?
Elasticsearch is a search engine based on the Lucene library. It provides a distributed, multitenant-capable full-text search engine 
with an HTTP web interface and schema-free JSON documents

### 56:-Celery? Why?
Celery is an open source asynchronous task queue or job queue which is based on distributed message passing. 
While it supports scheduling, its focus is on operations in real time


### 57:-Node JS
node js is a javaScript runtime environment that executes JavaScript code outside of a browser.


### 58:-MongoDB? Why?
MongoDB is a non-relational DMS .it store data that provides high performance, high availability, and automatic scaling

### 59:-Progressive Web App
A Progressive Web App (PWA) is a web app that uses modern web capabilities to deliver an app-like experience to users.


### 60:-Session based authentication
Session based authentication is one in which the user state is stored on the server’s memory. 
When using a session based auth system, the server creates and stores the session data in the server memory
when the user logs in and then stores the session Id in a cookie on the user browser.
The session Id is then sent on subsequent requests to the server and the server compares 
it with the stored session data and proceeds to process the requested action.


### 61:-Token based authentication
Token based authentication is one in which the user state is stored on the client.  
In this  , the user data is encrypted into a JWT (JSON Web Token) with a secret and then sent back to the client.
The JWT is then stored on the client side mostly localStorage and sent as a header for every subsequent request.
The server receives and validates the JWT before proceeding to send a response to the client.

### 62:-Authorization
Authorization is to give permission to access the information and access control in particular area.

### 63:-Docker
Docker is a set of platform as a service products that use OS-level virtualization to deliver software in packages called containers.
Containers are isolated from one another and bundle their own software, libraries and configuration files; 
they can communicate with each other through well-defined channels

### 64:-IaaS
Infrastructure as a service (IaaS) is a form of cloud computing that provides virtualized computing resources over the internet.


### 65:-AWS
Amazon Web Services is a subsidiary of Amazon that provides on-demand cloud computing platforms 
and APIs to individuals, companies, and governments, on a metered pay-as-you-go basis

### 66:-PaaS
Platform as a service (PaaS) is a cloud computing model in which a third-party provider delivers hardware and software tools 
-- usually those needed for application development -- to users over the internet.


### 67:-Heroku 
One of the first cloud platforms, Heroku has been in development since June 2007, 
Heroku is a platform as a service (PaaS) that enables developers to build, run, and operate applications entirely in the cloud.



### 68:-Hoisting
Hoisting is JavaScript's default behavior of moving declarations to the top,
first function is called then it is declared.

### 69:-Pass by Reference/Pass By Value
pass by value means actual value of variable is passed
pass by reference means reference to the memory location of the variable is passed

### 70:-closure
closure gives you access to an outer function's scope from an inner function

### 71:-	Prototypal Inheritance 
A prototype is a working object instance. Objects inherit directly from other objects


### 72:-Mutable Methods in JS
Updating state applies across all references to that variable

### 73:-Immutable Methods in JS
Changing the internal state of the data, so the reference always gets reassigned to a new object

### 74:-React
React is a JavaScript library for building user interfaces.

### 75:-Why React?
React is used to build single page applications. 
React allows us to create reusable UI components.

### 76:-State
it is an object that represents the parts of the app that can change

### 77:- Props
props stand for properties nad is used for passing data from one component to other component

### 78:- redux
redux is a javaScript library for managing application state

### 79:- Why Redux?
 it helps us manage the data  display and how we respond to user actions