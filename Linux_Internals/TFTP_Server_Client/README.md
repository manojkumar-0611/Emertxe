# TFTP Server and Client

## Overview

This project implements the Trivial File Transfer Protocol (TFTP) using UDP sockets. The application consists of a server and a client capable of transferring files across a network while following TFTP communication procedures.

The project demonstrates low-level network programming and protocol implementation in Linux.

## Features

* File upload and download
* UDP-based communication
* Packet acknowledgment handling
* Error detection and reporting
* Client-server architecture
* Reliable file transfer mechanism

## Technologies Used

* C Programming
* Socket Programming
* UDP Protocol
* Linux Networking APIs

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

* UDP socket programming
* Network protocol implementation
* Packet processing
* Client-server communication
* File transfer techniques
