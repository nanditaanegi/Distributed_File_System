# Distributed_File_System
This project implements a simplified Distributed File System (DFS) using the C programming language and socket-based communication on Windows.
The system follows a client–server architecture and consists of three main components: Client, NameNode, and DataNodes.
Client: Provides a menu-driven interface to store, retrieve, and list files while coordinating with the NameNode and DataNodes.
NameNode: Manages file metadata including file names, block mapping, and DataNode locations without storing actual data.
DataNode: Stores file blocks in memory and serves client requests for data storage and retrieval with replication support.
This project demonstrates core distributed system concepts such as metadata management,replication, client-server communication, and modular system design.
