# Memcached Lite 

Memcached is a distributed memory system that reduces the load on the database and increases the rate with the web applications can fetch and store data. In this assignment, a lite version of memcached server has been implemented. In this version of the server stores and retrieves a pair of key-value from multiple clients concurrently. Contrasting to the traditional memcache, in this version, this key-value pair is stored on a file system, which makes it easier for the clients to store the data even after the server process dies.
