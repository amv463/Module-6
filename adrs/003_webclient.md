# Choice of Business Logic Layer

# Status: accepted

# Context:

Python is an interpreted high-level general purpose programming language that 
emphasizes code readability and provides constructs that enable clear programming
on both small and large scales.

ZeroMQ is a high-performance asynchronous messaging library that provides a message
queue. This can be done when ran without a dedicated message broker. 

# Decision:

I chose to work with a Python web server due to pass experience I have had with 
using Python on previous projects. While I could of went with a different program 
such as the commonly deployed web server Apache, I felt that trying something
different would expand my skills. Though building a server in Python would be a 
insecure web server, building source code for it is very simplistic.  

I chose to use the ZeroMQ software to allow for message queues for the clientele using
the web server by connecting with the database for the server. Furthermore, it
runs well with simple and fast languages such as Python or C. ZeroMQ offers several 
different patterns that we learned in class such as Request-Reply, Publish-Subscribe, 
and Push-Pull patterns. The use of these patterns will allow for messaging that can be 
implemented across multiple platforms. 

# Consequences:

It is very simple to build source code when building a web server in Python. In 
addition, ZeroMQ allows things to run efficiently while being able to be easily 
implemented across multiple platforms.
 
