# Messaging Implementation

# Status: accepted

# Context:

ZMQ is a high-performance asynchronous messaging library that provides a message
queue. This can be done when ran without a dedicated message broker. 

# Decision:

I chose to use the ZeroMQ software to allow for message queues for the clientele using
the web server by connecting with the database for the server. Furthermore, it
runs well with simple and fast languages such as Python or C. ZeroMQ offers several 
different patterns that we learned in class such as Request-Reply, Publish-Subscribe, 
and Push-Pull patterns. The use of these patterns will allow for messaging that can be 
implemented across multiple platforms.

# Consequences:

It runs efficiently while being able to be easily implemented across multiple 
platforms.
