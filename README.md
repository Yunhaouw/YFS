# YFS
YFS(Yet another file system) is a simple distributed file system implementation in the spirit of MIT's graduate courses in Distributed Systems -- 6.824.

The file system is implemented in C++ programing language. Include the following parts:

- Lock Server
- Basic File Server
- MKDIR, UNLINK, and Locking
- Caching Lock Server
- Caching Extent Server + Consistency
- Paxos
- Replicated lock server

I am also planning to implement an additional features ontop of the existing file systems, currently, the idea will be -- distributed storage(load balancing using consistent hashing, just as in Chord)
