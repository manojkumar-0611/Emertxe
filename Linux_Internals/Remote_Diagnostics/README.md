# Remote Diagnostics

## Overview

Remote Diagnostics is a client-server application that enables remote monitoring and retrieval of system information from Linux machines. The application collects diagnostic data and transmits it securely across the network.

This project demonstrates system-level programming combined with networking concepts.

## Features

* Remote system monitoring
* Process information retrieval
* Memory usage reporting
* CPU statistics collection
* Network communication
* Command execution and response handling

## Technologies Used

* C Programming
* Linux System Calls
* Socket Programming
* TCP/IP Networking

## Build and Run

### Server

```bash
make
./server
```

### Client

```bash
./client <server_ip> <port>
```

## Learning Outcomes

* Linux system programming
* Remote monitoring techniques
* Network communication
* Resource management
* Client-server application design
