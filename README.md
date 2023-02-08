# Resource--System-design-basic-guide

![photo1674908855](https://user-images.githubusercontent.com/41374671/217578395-e589a283-1f32-43a5-9be5-8a43b3ce8ae0.jpeg)


Here is a brief introduction of  some of the components involved:

𝗔𝗣𝗜 𝗚𝗮𝘁𝗲𝘄𝗮𝘆
An API Gateway (AG) is a server that acts as a single point of entry for a set of #microservices. AG receives client requests, forwards them to the appropriate microservice, and then returns the server's response to the client. AG is responsible for tasks such as routing, authentication, and rate limiting.


𝗖𝗗𝗡
A Content Delivery Network (CDN) is a distributed network of servers that are deployed in multiple locations around the world. These servers are designed to deliver web content, such as images, videos, and other static files, to users based on their geographical location. The main purpose of a #cdn is to improve the performance and availability of web content by caching it on servers that are closer to the users who are requesting it.


𝗗𝗮𝘁𝗮 𝗣𝗮𝗿𝘁𝗶𝘁𝗶𝗼𝗻𝗶𝗻𝗴
In a database, 𝗵𝗼𝗿𝗶𝘇𝗼𝗻𝘁𝗮𝗹 𝗽𝗮𝗿𝘁𝗶𝘁𝗶𝗼𝗻𝗶𝗻𝗴, also known as sharding, involves dividing the rows of a table into smaller tables and storing them on different servers or database instances. This is done to distribute the load of a database across multiple servers and to improve performance.

On the other hand, 𝘃𝗲𝗿𝘁𝗶𝗰𝗮𝗹 𝗽𝗮𝗿𝘁𝗶𝘁𝗶𝗼𝗻𝗶𝗻𝗴 involves dividing the columns of a table into separate tables. This is done to reduce the number of columns in a table and to improve the performance of queries that only access a small number of columns.


𝗗𝗶𝘀𝘁𝗿𝗶𝗯𝘂𝘁𝗲𝗱 𝗺𝗲𝘀𝘀𝗮𝗴𝗶𝗻𝗴 𝘀𝘆𝘀𝘁𝗲𝗺𝘀 
These are used to send messages between distributed components of a system. Examples include Apache #kafka and #rabbitmq.


𝗗𝗶𝘀𝘁𝗿𝗶𝗯𝘂𝘁𝗲𝗱 𝗳𝗶𝗹𝗲 𝘀𝘆𝘀𝘁𝗲𝗺𝘀
These are file systems that are designed to store and manage files across a group of servers.


𝗡𝗼𝘁𝗶𝗳𝗶𝗰𝗮𝘁𝗶𝗼𝗻𝘀 𝘀𝘆𝘀𝘁𝗲𝗺
These are used to send notifications or alerts to users, such as emails, push notifications, or text messages. 


𝗙𝘂𝗹𝗹-𝘁𝗲𝘅𝘁 𝘀𝗲𝗮𝗿𝗰𝗵
Full-text search enables users to search for specific words or phrases within an app or website. When a user queries, the app or website returns the most relevant results. To do this quickly and efficiently, full-text search relies on an inverted index, which is a data structure that maps words or phrases to the documents in which they appear.


Ref:
✅System Design Survival Guide (2023): https://lnkd.in/deqz6gnz
✅Take a look at 𝗚𝗿𝗼𝗸𝗸𝗶𝗻𝗴 𝘁𝗵𝗲 𝗦𝘆𝘀𝘁𝗲𝗺 𝗗𝗲𝘀𝗶𝗴𝗻 𝗜𝗻𝘁𝗲𝗿𝘃𝗶𝗲𝘄 for #systemdesign #interview questions - https://lnkd.in/g4Wii9r7
✅For software architecture, take a look at 𝗚𝗿𝗼𝗸𝗸𝗶𝗻𝗴 𝘁𝗵𝗲 𝗔𝗱𝘃𝗮𝗻𝗰𝗲𝗱 𝗦𝘆𝘀𝘁𝗲𝗺 𝗗𝗲𝘀𝗶𝗴𝗻 𝗜𝗻𝘁𝗲𝗿𝘃𝗶𝗲𝘄 - https://lnkd.in/dyCRtiec
