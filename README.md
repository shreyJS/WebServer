# Java Web Servers

This repository contains three implementations of web servers in Java:
1. Single-Threaded Web Server
2. Multi-Threaded Web Server
3. Multi-Threaded Web Server Using Thread Pool

This project demonstrates core concepts of ***Computer Networks*** and ***Operating Systems*** alongwith their applications.

## Table of Contents
- [Single-Threaded Web Server](#single-threaded-web-server)
- [Multi-Threaded Web Server](#multi-threaded-web-server)
- [Multi-Threaded Web Server Using Thread Pool](#multi-threaded-web-server-using-thread-pool)
- [Requirements](#requirements)
- [Usage](#usage)
- [Contributing](#contributing)

## Single-Threaded Web Server 

A single-threaded web server processes one client request at a time. This means it can handle only one connection in its main thread of execution, which is suitable for basic applications or learning purposes.

## Multi-Threaded Web Server

In a multi-threaded web server, the main server thread listens for incoming connections. When a new connection is accepted, the server spawns a new thread to handle the request. This allows the main server thread to continue listening for and accepting new connections while existing requests are being processed concurrently.

## Multi-Threaded Web Server using Thread pool

A multi-threaded web server using a thread pool is an advanced type of multi-threaded server that manages a pool of pre-created threads to handle incoming client requests. Instead of creating a new thread for each request, the server reuses existing threads from the pool. This approach can improve performance and resource management, especially under high load.

## Requirements
- Java Development Kit (JDK) 8 or higher.

## Usage
1. Clone the repository:
```
git clone https://github.com/yourusername/java-web-servers.git
cd java-web-servers

```

2. Compile the Java files:
```
javac SingleThreadedWebServer.java
javac MultiThreadedWebServer.java
javac ThreadPooledWebServer.java

```

3. Run the desired web server:
```
java SingleThreadedWebServer
java MultiThreadedWebServer
java ThreadPooledWebServer

```

## Contributing
Contributions are welcome! Please submit a pull request or open an issue to discuss your ideas.
