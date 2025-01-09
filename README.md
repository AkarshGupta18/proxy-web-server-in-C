# proxy-web-server-in-C

Programming Language: C
Key Features:

Implemented a multithreaded proxy web server using semaphores for synchronization and concurrency control.
Designed a caching mechanism with the Least Recently Used (LRU) algorithm to improve response times and reduce server traffic.
Handled multiple client requests simultaneously while ensuring thread safety through locks and semaphores.
Developed the server to fetch data from a web server if not present in the cache, store the response, and return it to the client.
Explored OS concepts like threading, locking, and concurrency management.
Key Achievements:

Enhanced understanding of request handling between local clients and remote servers.
Improved server efficiency by reducing redundant requests using caching.
Addressed concurrency challenges and implemented safe multithreaded access to shared resources.
Limitations Addressed:

Limited cache size and client-specific responses were handled with predefined constraints.
Tools & Concepts:
Multithreading, Semaphores, Locks, LRU Cache Algorithm, Proxy Servers, C Programming.
